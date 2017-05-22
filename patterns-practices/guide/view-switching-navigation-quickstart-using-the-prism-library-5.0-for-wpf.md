---
TOCTitle: 'View-Switching Navigation QuickStart Using the Prism Library 5.0 for WPF'
Title: 'View-Switching Navigation QuickStart Using the Prism Library 5.0 for WPF'
ms:assetid: '46d425cd-d765-4866-ac90-2edb807b11db'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430881(v=PandP.40)'
---


# View-Switching Navigation QuickStart Using the Prism Library 5.0 for WPF

From: [Developer's Guide to Microsoft Prism Library 5.0 for WPF](/patterns-practices/index)

The View-Switching Navigation QuickStart sample demonstrates how to use the Prism Region Navigation API with the Model-View-ViewModel (MVVM) pattern. The Prism Region Navigation utilizes a Uniform Resource Identifier (URI) approach to switch between views. The QuickStart simulates the navigation of a simple email, contacts, and calendar application. The left region provides navigation to each of the main views. The views demonstrate backward navigation and asynchronous dialog interactions.

The View-Switching Navigation QuickStart is more complex than a typical QuickStart because it demonstrates multiple navigation scenarios. Navigation supports just-in-time view creation, and therefore, interacts with the dependency injection container. Additionally, to be compatible with the Model-View-ViewModel (MVVM) approach, navigation interacts with views and with view models (via the **DataContext** property).

This QuickStart demonstrates the following navigation capabilities:

-   Navigating to a view in a region
-   Navigating to a view in a region contained in another view (nested navigation)
-   Navigation journal support
-   Just-in-time view creation
-   Passing contextual information when navigating to a view
-   Views and view models participating in navigation, including confirming or canceling navigation
-   Using navigation as part of an application built through modularity and user interface (UI) composition

## Business Scenario


The main window of the View-Switching Navigation QuickStart shows a simple email client application. In this window, the navigation pane is located on the left of the screen and provides direct access to the application's features. These features are Mail, Calendar, and Contacts (which has the Details and the Avatars view). In the main pane, the selected feature is shown. Notice that the Mail feature is selected when the application starts. This is coordinated by the shell when the **Email** module is loaded.

Because the modules do not have dependencies between them, they are loaded and initialized in random order. To make sure that the items in the left pane are ordered, a **ViewSortHint** attribute is applied to each of the views. For more information about the **ViewSortHint** attribute, see [The Contacts Module (Navigation to a Nested View)](#_the_contacts_module) section.

The following illustration shows the QuickStart main window.


![](images/view-switching-navigation-quickstart.png "View-Switching Navigation QuickStart user interface")

**View-Switching Navigation QuickStart user interface**

> [!NOTE]
> The UI of the QuickStart has information icons. You can click them to display or hide information and implementation notes about the different pieces of the QuickStart.

## Building and Running the QuickStart

This QuickStart requires Microsoft Visual Studio 2012 or later and the .NET Framework 4.5.1.

**To build and run the View-Switching Navigation QuickStart**

1.  In Visual Studio, open the solution file Quickstarts\\View-Switching Navigation\_Desktop\\ ViewSwitchingNavigation.sln.
2.  In the **Build** menu, click **Rebuild Solution**.
3.  Press **F5** to run the QuickStart.

## Implementation Details

The QuickStart highlights the key elements that you should consider when you use the navigation features provided by the Prism Library to implement navigation in a composite application. In this approach, the user interface is divided among different modules. Each module populates the navigation region on the left side, and participates in navigation to coordinate the view in the main content region on the right side. This section describes the key artifacts of the QuickStart. The following figure shows the workflow that occurs when a user navigates from one location to another.

![](images/prism-region-navigation-workflow.png "Prism Region Navigation Workflow")

Prism Region Navigation Workflow

## Navigation Support in the Prism Library


The Prism Library supports navigation through the use of *regions*. Navigation classes and components are located in the **Microsoft.Practices.Prism.Regions** namespace. Each region implements the **INavigateAsync** interface, as shown in the following code example.

```C#
    public interface IRegion : INavigateAsync, INotifyPropertyChanged
    {
        ...
    }
```

The **IRegion** interface provides the **NavigationService** property to allow navigation between regions. Each region has its own **NavigationService**, and each **NavigationService** has its own **Journal**, or record of the current, past, and future navigation within the region. The **NavigationService** returns an **IRegionNavigationService**. The **IRegionNavigationService** interface is shown in the following code example.

```C#
    public interface IRegionNavigationService : INavigateAsync
    {
        IRegion Region { get; set; }

        IRegionNavigationJournal Journal { get; }

        event EventHandler<RegionNavigationEventArgs> Navigating;

        event EventHandler<RegionNavigationEventArgs> Navigated;

        event EventHandler<RegionNavigationFailedEventArgs> NavigationFailed;

    }
```

The **NavigationService** has a reference to the region to which it belongs and a reference to the navigation journal. Additionally, it contains the **Navigating** and **Navigated** events. The **Navigating** event is triggered during navigation to a page, and the **Navigated** event is raised when the region is navigated to content.

The method from the service that is used to navigate is **RequestNavigate**. This method requires the navigation target and a callback that will be invoked when the navigation is complete.

This method initiates the workflow described in the preceding figure, where it calls the **DoNavigate** method of the service with the source and the callback. It then calls **RequestCanNavigateOnCurrentlyActiveViews**. The callback is invoked when navigation ends, whether or not the navigation is successful. After the callback, the active views and their view models are queried to determine if they implement the **IConfirmNavigationRequest** interface. If they implement this interface, the user will be prompted when he or she navigates away from that view. Finally, the **ExecuteNavigation** method is invoked. This method is shown in in the following code example.

```C#
    private void ExecuteNavigation(NavigationContext navigationContext, object[] activeViews, Action<NavigationResult> navigationCallback)
    {
        try
        {
            NotifyActiveViewsNavigatingFrom(navigationContext, activeViews);

            object view = this.regionNavigationContentLoader.LoadContent(this.Region, navigationContext);

            // Raise the navigating event just before activing the view.
            this.RaiseNavigating(navigationContext);

            this.Region.Activate(view);

            // Update the navigation journal before notifying others of navigaton
            IRegionNavigationJournalEntry journalEntry = this.serviceLocator.GetInstance<IRegionNavigationJournalEntry>();
            journalEntry.Uri = navigationContext.Uri;
            this.journal.RecordNavigation(journalEntry);

            // The view can be informed of navigation
            InvokeOnNavigationAwareElement(view, (n) => n.OnNavigatedTo(navigationContext));

            navigationCallback(new NavigationResult(navigationContext, true));

            // Raise the navigated event when navigation is completed.
            this.RaiseNavigated(navigationContext);
        }
        catch (Exception e)
        {
            this.NotifyNavigationFailed(navigationContext, navigationCallback, e);
        }
    }
```

The preceding method notifies the active views that the user is navigating away from them, acquires the target view through the content loader, activates the target view, and then updates the journal. The view and the view model are then informed that the user is navigating to them, the callback is invoked, and the navigation completed event is raised.

## The Journal

The journal is a stack that maintains the history of the navigated views. It stores the forward, current, and backward history of visited pages. The **RecordNavigation** method is used for registering the current view in the stack. The journal avoids adding a view to the stack if you are internally navigating the journal views.

> [!NOTE]
> It is important that you carefully define your application Uniform Resource Identifier (URI) structure before you implement navigation.

## Using the Prism Library for Navigation

This section describes how the QuickStart uses the Prism Library to demonstrate navigation. The Shell view has two regions: the navigation region and the main region. You can see the region definition in the following code located in the ViewSwitchingNavigation\\Shell.xaml file.

```XAML
    <Grid x:Name="LayoutRoot"
              Background="{StaticResource MainBackground}">
        ...
            <Border Grid.Column="0" Grid.Row="2" Background="LightGray" MinWidth="250" Margin="5,0,0,5">
                <ItemsControl x:Name="NavigationItemsControl" prism:RegionManager.RegionName="MainNavigationRegion" Grid.Column="0" Margin="5" Padding="5" />
            </Border>
            <ContentControl prism:RegionManager.RegionName="MainContentRegion" 
                            Grid.Column="1" Grid.Row="2" Margin="5,0,5,5" HorizontalContentAlignment="Stretch" VerticalContentAlignment="Stretch"/>

        </Grid>
    </Grid>
```

Each QuickStart module (Mail, Calendar, and Contacts) registers the navigation buttons in the navigation region, and the corresponding views (the ones that hold the specific feature) in the main content region.

The shell contains code that ensures that the email view is navigated to when the email module is loaded. Because of this, the email view is shown when the application starts. The section of the following code that appears in bold demonstrates this.

```C#
    [Export]
    public partial class Shell : UserControl, IPartImportsSatisfiedNotification
    {
        private const string EmailModuleName = "EmailModule";
        private static Uri InboxViewUri = new Uri("/InboxView", UriKind.Relative);
        public Shell()
        {
            InitializeComponent();
        }

        [Import(AllowRecomposition = false)]
        public IModuleManager ModuleManager;

        [Import(AllowRecomposition = false)]
        public IRegionManager RegionManager;

        public void OnImportsSatisfied()    {        this.ModuleManager.LoadModuleCompleted +=            (s, e) =>            {                if (e.ModuleInfo.ModuleName  EmailModuleName)                {                    this.RegionManager.RequestNavigate(                        RegionNames.MainContentRegion,                        InboxViewUri);                }            };    }
    }
```

## The Calendar Module (Cross-Navigation to Other Modules)

The Calendar module shows cross-navigation to another area/module. The following code example shows the **Initialize** method of the Calendar module.

```C#
    public void Initialize()
    {
        this.regionManager.RegisterViewWithRegion(RegionNames.MainNavigationRegion, typeof(CalendarNavigationItemView));
    }
```

The **Initialize** method registers the **CalendarNavigationItemView** view, which is the button used for displaying the calendar feature. The **CalendarView** view could have been registered here, but we are using a different mechanism to make the view available to the region (through just-in-time creation during navigation).

The event handler of this button uses the region manager to call the **RequestNavigate** method, passing the name of the region, and the URI to navigate to, as shown in the following code example.

```C#
    private void Button_Click(object sender, RoutedEventArgs e)
    {            
        this.regionManager.RequestNavigate(RegionNames.MainContentRegion, calendarViewUri);
    }
```

When the navigation is completed—that is, when calendar view is loaded in the main region and the **Navigated** event is triggered—the button is checked to inform the user that the view displayed in the main region is the calendar. This is shown in the following code example. Every module of the QuickStart has similar code to perform these tasks.

```C#
    public void MainContentRegion_Navigated(object sender, RegionNavigationEventArgs e)
    {
        this.UpdateNavigationButtonState(e.Uri);
    }

    private void UpdateNavigationButtonState(Uri uri)
    {
        this.NavigateToCalendarRadioButton.IsChecked = (uri  calendarViewUri);
    }
```

Because this QuickStart implements the MVVM pattern, the logic is located in the view model classes (except for the navigation item views). You can construct URIs that use a query string to pass context to a view or view model. For example, in the view model class of the Calendar view, when a user clicks a meeting, a query string is used to identify the email message to display. You can see the building of the URI and the request to navigate in the following code example.

```C#
    private void OpenMeetingEmail(Meeting meeting)
    {
        var parameters = new NavigationParameters();
        parameters.Add(EmailIdName, meeting.EmailId.ToString(GuidNumericFormatSpecifier));

        this.regionManager.RequestNavigate(RegionNames.MainContentRegion, new Uri(EmailViewName + parameters, Urikind.Relative));
    }
```

In the preceding code, using Prism's **NavigationParameters** class, the ID of a specific mail is specified. This class forms query parameters to be added to the queries by taking the name and the value of the parameter. The **ToString** method of this class is overridden to create a query string with all the specified parameters. This example shows how to use the **NavigationParameters** class to pass string parameters using the Query String, but it can also be used to pass object parameters, using an overload of the **RequestNavigate** method. Finally, the query is appended to the name of the view. The result will be similar to that shown in the following illustration.

![](images/a-complex-uri-structure.png "A complex URI structure")

A complex URI structure

Finally, using the **RequestNavigate** method, the region will navigate to the created Uri.

## The Contacts Module (Navigation to a Nested View)

The Contacts module demonstrates navigation to a view nested within another view's region. The views in this module implement the **INavigationAware** interface to participate in the navigation. The contacts view has a region in which a sub-view is displayed.

There are two navigation item views for the contact module: one for displaying contact details and the other to display contact avatars. Each option has a different URI and click event handler, as shown in the following code located in the ViewSwitchingNavigation.Contacts\\Views\\ContactsDetailNavigationItemView.xaml.cs file.

```C#
    [Export]
    [ViewSortHint("03")]
    public partial class ContactsDetailNavigationItemView : UserControl, IPartImportsSatisfiedNotification
    {
        private const string mainContentRegionName = "MainContentRegion";

        private static Uri contactsDetailsViewUri = new Uri("ContactsView?Show=Details", UriKind.Relative);

        ...


        private void NavigateToContactDetailsRadioButton_Click(object sender, RoutedEventArgs e)
        {
            this.regionManager.RequestNavigate(mainContentRegionName, contactsDetailsViewUri);
        }
    }
```

In the preceding code, the **ViewSortHint** attribute is used to specify the order in which views will be shown. In this case, the **ContacstViewNavigationItem** is placed third in the list. An alphanumeric comparison of the sort hints occurs to determine the order. This is used for placing the navigation buttons of the QuickStart in the same order in every run.

A view or a view model should implement the **INavigationAware** interface when it needs to be notified of navigation activities and so that it can receive the URI query. This interface provides the following navigation events.

-   **IsNavigationTarget**. Called to determine if this instance can handle the navigation request.
-   **OnNavigatedFrom**. Called when the implementer is being navigated away from.
-   **OnNavigatedTo**. Called when the implementer has been navigated to.

The contact view implements the **INavigationAware** interface. When the contact view is navigated to, using any of the navigation buttons or by going back, the **OnNavigatedTo** event is used to determine which sub-view will be loaded, based on the URI query. This can be seen in the following code, extracted from the ViewSwitchingNavigation.Contacts\\Views\\ContactsView.xaml.cs file.

```C#
    void INavigationAware.OnNavigatedTo(NavigationContext navigationContext)
    {
        // Navigating an inner region based on context
        // The ContactsView will navigate an inner region based on the
        // value of the 'Show' query parameter.  If the value is 'Avatars'
        // we will navigate to the avatar view otherwise we'll use the details view.
        NavigationParameters parameters = navigationContext.Parameters;
        if (parameters != null && string.Equals(parameters[ShowParameterName].ToString(), AvatarsValue))
        {
            regionManager.RequestNavigate(ContactsRegionNames.ContactDetailsRegion, new Uri(ContactAvatarViewName, UriKind.Relative));
        }
        else
        {
            regionManager.RequestNavigate(ContactsRegionNames.ContactDetailsRegion, new Uri(ContactDetailViewName, UriKind.Relative));
        }
    }
```

In the preceding code, the view that will be loaded in the inner region of the contact view depends on the value of the **Show** parameter of the URI query.

The first time you navigate to any of these views, the specified view will be created by the **NavigationService**.

## The Email Module

The Email feature demonstrates navigation to a view that handles additional navigation based on user activity. The view models in this module implement the **INavigationAware** interface to participate in the navigation.

In the Email module, most of the work is performed by the view models. This module is composed of three views: mail list (**InboxView** view), open mail (**EmailView** view), and compose email (**ComposeEmailView** view). The following code example shows the methods that handle the **New**, **Reply**, and **Open** button actions. Notice that they just create a query string and then navigate to the corresponding view in the main region.

```C#
    private void ComposeMessage(object ignored)
    {
        this.regionManager.RequestNavigate(RegionNames.MainContentRegion, ComposeEmailViewUri);
    }

    private void ReplyMessage(object ignored)
    {
        var currentEmail = this.Messages.CurrentItem as EmailDocument;
        if (currentEmail != null)
        {
            var parameters = new NavigationParameters();
            parameters.Add(ReplyToKey, currentEmail.Id.ToString("N"));         this.regionManager.RequestNavigate(RegionNames.MainContentRegion, ComposeEmailViewKey + parameters);
        }
    }

    private bool CanReplyMessage(object ignored)
    {
        return this.Messages.CurrentItem != null;
    }

    private void OpenMessage(EmailDocument document)
    {
        NavigationParameters parameters = new NavigationParameters();
        parameters.Add(EmailIdKey, document.Id.ToString("N"));     this.regionManager.RequestNavigate(RegionNames.MainContentRegion, new Uri(EmailViewKey + parameters, UriKind.Relative));
    }
```

The **ComposeEmailViewModel** implements the **IConfirmNavigationRequest** interface used for determining whether the view or view model accepts being navigated away from. This interface has the **ConfirmNavigationRequest** method that allows the cancelation of a navigation request. In the compose email screen, the user might start writing a message, but not send it. Therefore, the user should be prompted to confirm that he or she wants to discard the message before navigating away. The following code shows the implementation of the **ConfirmNavigationRequest** method in the **ComposeEmailViewModel** class. The view model uses the **InteractionRequest** to prompt the user, and if the user confirms that he or she wants to navigate away, the navigation continues when **continuationCallback** is passed as a parameter.

> [!NOTE]
> You must invoke the **continuationCallback** action or you will halt this current navigation request and no further processing of this request will take place.

```C#
    void IConfirmNavigationRequest.ConfirmNavigationRequest(NavigationContext navigationContext, Action<bool> continuationCallback)
    {
        if (this.sendState  NormalStateKey)
        {
            this.confirmExitInteractionRequest.Raise(
                new Confirmation { Content = Resources.ConfirmNavigateAwayFromEmailMessage, Title = Resources.ConfirmNavigateAwayFromEmailTitle },
                c => { continuationCallback(c.Confirmed); });
        }
        else
        {
            continuationCallback(true);
        }
    }
```

In the **ComposeEmailViewModel** class, the **OnNavigatedTo** method is used to determine if the user is composing a new email message or replying to an existing one. The navigation context offers the context information through the **Parameters** property, which is a string/object dictionary built from the parameters passed in the **RequestNavigate** method or through the navigation URI. In the following code example, if the **ReplyTo** parameter contains a value, the relevant information from the email service will be retrieved to populate the response values. If not, an empty email will be displayed.

```C#
    void INavigationAware.OnNavigatedTo(NavigationContext navigationContext)
    {
        var emailDocument = new EmailDocument();
        var parameters = navigationContext.Parameters;
        var replyTo = parameters[ReplyToParameterKey];
        Guid replyToId;
        if (replyTo != null && Guid.TryParse(replyTo, out replyToId))
        {
            var replyToEmail = this.emailService.GetEmailDocument(replyToId);
            if (replyToEmail != null)
            {
                emailDocument.To = replyToEmail.From;
                emailDocument.Subject = Resources.ResponseMessagePrefix + replyToEmail.Subject;

                emailDocument.Text =
                    Environment.NewLine +
                    replyToEmail.Text
                        .Split(Environment.NewLine.ToCharArray())
                        .Select(l => l.Length > 0 ? Resources.ResponseLinePrefix + l : l)
                        .Aggregate((l1, l2) => l1 + Environment.NewLine + l2);
            }
        }
        else
        {
            var to = parameters[ToParameterKey];
            if (to != null)
            {
                emailDocument.To = to;
            }
        }

        this.EmailDocument = emailDocument;
        this.navigationJournal = navigationContext.NavigationService.Journal;
    }
```

Notice that navigation journal is instantiated at the end of the preceding code. The journal is used to navigate to the previous view. The journal provides the **GoBack** method for navigating backwards in the navigating history. This is used after the user sends or cancels the composition of an email message. You can see this method's usage in the following code example.

```C#
    private void CancelEmail()
    {
        if (this.navigationJournal != null)
        {
            this.navigationJournal.GoBack();
        }
    }
```

## Unit and Acceptance Tests

The View-Switching Navigation QuickStart includes unit tests within the solution. Unit tests verify if individual units of source code work as expected.

**To run the View-Switching Navigation QuickStart unit tests**

1.  Build the Solution.
2.  Open **Test Explorer**.
3.  After building the solution, Visual Studio finds the tests. Click the **Run All** button to run the unit tests.

The View Switching Navigation QuickStart includes a separate solution that includes acceptance tests. The acceptance tests describe how the application should perform when you follow a prescribed series of steps. You can use the acceptance tests to explore the functional behavior of the application in a variety of scenarios.

**To run the View-Switching Navigation QuickStart acceptance tests**

1.  In Visual Studio, open the solution file QuickStarts\\View-Switching Navigation\_Desktop\\ViewSwitchingNavigation.Tests.AcceptanceTest\\ViewSwitching Navigation.Tests.AcceptanceTest.sln.
2.  Build the Solution.
3.  Open **Test Explorer**.
4.  After building the solution, Visual Studio finds the tests. Click the **Run All** button to run the acceptance tests.

## Outcome

You should see the QuickStart window and the tests automatically interact with the application. At the end of the test run, you should see that all tests have passed.

## More Information

To learn about other aspects of navigation in Prism, see the following topics:

-   [Navigation](/patterns-practices/guide/8-navigation-using-the-prism-library-5.0-for-wpf)
-   [State-Based Navigation QuickStart](/patterns-practices/guide/state-based-navigation-quickstart-using-the-prism-library-5.0-for-wpf)

To learn about other code samples included with Prism, see the following topics:

-   [Stock Trader Reference Implementation](/patterns-practices/guide/stock-trader-reference-implementation-using-the-prism-library-5.0-for-wpf)
-   [Modularity QuickStarts](/patterns-practices/guide/modularity-quickstarts-using-the-prism-library-5.0-for-wpf)
-   [Interactivity QuickStart](/patterns-practices/guide/interactivity-quickstart-using-the-prism-library-5.0-for-wpf)
-   [MVVM QuickStart](/patterns-practices/guide/mvvm-quickstart-using-the-prism-library-5.0-for-wpf)
-   [Commanding QuickStart](/patterns-practices/guide/commanding-quickstart-using-the-prism-library-5.0-for-wpf)
-   [UI Composition QuickStart](/patterns-practices/guide/ui-composition-quickstart-using-the-prism-library-5.0-for-wpf)
-   [Event Aggregation QuickStart](/patterns-practices/guide/event-aggregation-quickstart-using-the-prism-library-5.0-for-wpf)

