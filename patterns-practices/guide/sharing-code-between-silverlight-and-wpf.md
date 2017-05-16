---
TOCTitle: Sharing Code Between Silverlight and WPF
Title: Sharing Code Between Silverlight and WPF
ms:assetid: '362547b4-30f0-443a-9587-b7685ee4289e'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Ff921109(v=PandP.40)'
---

# Sharing Code Between Silverlight and WPF


This topic helps you understand multi-targeting from a Prism perspective and its advantages and disadvantages. Multi-targeted code targets two different platforms with largely the same code-base. This allows binaries targeting two different technologies to be produced while keeping the code as much the same as possible. In this case, the technologies this topic describes are Windows Presentation Foundation (WPF) and Silverlight. This topic includes some considerations you should think about when developing multi-targeting applications for these technologies.

## Goal and Benefits

When writing applications for WPF and Silverlight that have similar features and capabilities, it makes sense to strive for a single code-base. Although the WPF and Silverlight platforms are very similar, they have limited binary compatibility. Only Silverlight 4 assemblies that reference a certain set of core, portable framework assemblies can be loaded into the .NET Framework 4.0 runtime.

Because Prism offers largely the same capabilities for both WPF and Silverlight, much of your code can be built that targets both of these technologies. Supporting multi-targeted applications is primarily about implementing the patterns and infrastructure that maximize the possibility for sharing code and components between the two environments, and for allowing an application to integrate environment-specific functionality so that it can take full advantage of desktop or browser-specific features. By creating your multi-targeting composite application using Prism, you can reuse source code across WPF and Silverlight applications.

## Out of Scope

If you can structure your assemblies to take advantage of the binary compatibility support between Silverlight and WPF, you should do so. For more information about this, see the CLR Team Blog post, "[Sharing Silverlight Assemblies with .NET Apps](http://blogs.msdn.com/b/clrteam/archive/2009/12/01/sharing-silverlight-assemblies-with-net-apps.aspx)."

This topic is not intended to describe this scenario; instead, it describes the challenges and solutions for building multi-targeted applications by sharing source code.

## Multi-Targeting Scenarios

The primary scenario is for applications that deliver both a feature-rich desktop experience and a wide-reach Internet application experience. In this scenario, you may want to develop an application that has the same features and workflow on WPF and Silverlight or one that offers different features and workflows. The following are some applications of multi-targeting:

-   You can provide users with a full-featured application while they are in the office and a scaled, browser-based version for when they are traveling.
-   You can provide internal users with a desktop-based application and external customers or partners with a browser-hosted application.

For example, a business may have both a call-center application for customers who want to place their orders over the phone and an online order application for customers who want to place their orders online. However, the forms are not the exactly the same. The call-center desktop order form offers more information and expanded functionality than the online order form. However, because they accomplish similar things there will be certain parts of the order form and business logic that can be reused across both scenarios.

Service-oriented applications are easier to multi-target because Silverlight is inherently service-oriented. Silverlight does not have support for local storage or database access because of its targeted feature set and security restrictions. Additionally, connected applications are also easier to multi-target because of Silverlight's connected nature.

## Multi-Targeted Considerations

By making your solution multi-targetable, you should also consider the following:

-   Silverlight offers limited storage on the local client computer in isolated storage.
-   You may lose simplicity and readability of code in your multi-targetable solution. Because some features of WPF are not available in Silverlight, you will need to work around these issues and your code may not be as elegant or readable.
-   By default, Silverlight applications execute in a secure sandbox, so there are a several things that you cannot do outside of the sandbox context. These applications have restricted access to the local computer and are constrained to help prevent malicious behavior. These restrictions prevent access to devices and interacting with other running programs.

    **Note:** If you need access to some of these items, you can create an out-of-browser Silverlight application with elevated trust. For more information, see "[Trusted Applications](http://msdn.microsoft.com/en-us/library/ee721083(vs.95).aspx)" on MSDN.

-   Silverlight supports only asynchronous communications, so you cannot multi-target applications that use synchronous communications.

## Multi-Targeted Elements

Typically there is a significant amount of code that is unrelated to the actual presentation technology. Because of the very close nature of the Silverlight and .NET Framework runtimes, the bulk of this code can be shared between both technologies. This also encourages heavy use of Separated Presentation patterns to isolate the logic of the presentation from the actual visual presentation, to help maximize the separation between user interface (UI) and non-UI code. Usually, you can multi-target the following source code elements:

-   **Presentation patterns**. Patterns such as Model-View-ViewModel (MVVM), Model-View-Presenter (MVP), and Model-View-Controller (MVC) can be used if the logic is largely the same across the platforms.
-   **Services**. Services that assist in presentation can often be multi-targeted.
-   **Unit tests**. Many unit tests can be multi-targeted with tools, such as the Silverlight Unit Test, Framework that use the same attribute structure as MSTest.
-   **Simple views**. If the XAML used is supported by both Silverlight and WPF. If a view consists of only basic controls and simple data binding, it is possible that it can also be shared between WPF and Silverlight.

Silverlight's API is largely a subset of the .NET Framework's API, so it often makes sense to develop your application against this smaller API to reduce the chance of using a feature not available for both platforms. Because of the differences between the XAML in Silverlight and WPF, the following elements are harder to reuse:

-   Complex views (XAML)
-   Controls
-   Styling
-   Animation
-   Expression Blend behaviors and triggers

## A Solution to Multi-Targeting: Multiple Linked Projects

Silverlight and WPF have only limited binary compatible, so some code and components have to be recompiled for each target environment. The approach Prism takes is to provide guidance on structuring application and module code into multiple linked projects. Each project manages all the references, resources, and code specific to the WPF or Silverlight target environment. Code that is shared is linked between two projects so that it is automatically compiled into each target. Unit tests can similarly be shared between the two environments, so that they can be written once and run against the target code in either of the two target environments. The Prism team created a tool named Project Linker to help create and maintain these links. The Project Linker was used to link projects in the Prism Library, QuickStarts, and reference implementations.

**Note:** You can download [Project Linker](http://visualstudiogallery.msdn.microsoft.com/en-us/5e730577-d11c-4f2e-8e2b-cbb87f76c044) from Visual Studio Gallery or open Visual Studio, click **Extension Manager** on the **Tools** menu, click **Online Gallery** in the **Extension Manager** dialog box, and then search for "Project Linker."

Non-UI code and components are probably going to be the easiest to share, so adhering to separated UI patterns is essential in making sure that the UI and non-UI pieces of the application or modules are cleanly separated.

## Core Application

The overall pattern is based on defining the core application in shared code and then augmenting that with extensions that implement WPF (desktop) or Silverlight (browser) specific functionality. The core application defines the overall structure of the application and contains the application code and components that are common to the two environments. Silverlight is largely a subset of WPF, so developing the core application in Silverlight reduces the risk of relying on an API or feature that is available in WPF but not in Silverlight.

**Note:** Many solutions in the Prism source tree actually have the core source files in the WPF projects and the Silverlight projects link to the files in the WPF projects. This is mostly because of historical reasons since the first version of Prism was built prior to the first Silverlight release.

The following illustration shows the Solution Explorer view for the Multi-Targeted QuickStart. Most files in the WPF version of the QuickStart are linked files because the core application was developed in Silverlight. The shared files found in the QuickStart are images, models, services, interfaces, and resources. The shared (linked) files are highlighted.

Shared files in the Multi-Targeting QuickStart

![](https://msdn.microsoft.com/en-us/Ff921109.B797DC251AF61200B5C7992B5AA6297C(en-us,PandP.40).png "Shared files in the Multi-Targeting QuickStart")

## Creating Multi-Targeted Applications

This section describes three areas to consider when developing a multi-targeted application:

-   Design and Code Guidelines. This section describes considerations for sharing code between Silverlight and WPF.
-   Process Guidelines. This section describes approaches for sharing code between Silverlight and WPF.
-   Team Build Guidelines. This section describes specific Microsoft Team Build issues when building multi-targeted applications.
-   Contrasting Silverlight and WPF. This section describes differences between Silverlight 4 and WPF.

## Design and Code Guidelines

Design and code guidelines include the following:

-   Use Separated Presentation patterns to maximize the amount of shared code.
-   Where possible, write code so it compiles on both platforms. When this is not possible, do the following:
    -   Use \#if statements if you have simple or single line constructs.
    -   Use partial classes when most of the class is similar but some methods have platform-specific implementations.
    -   Use partial methods only if you need to call an extra method on one platform but not the other.
    -   Build platform-specific classes with a single responsibility.
-   Create a solution folder for Silverlight and another for WPF.
-   Check Silverlight and WPF references when refactoring code.

The next sections describe each of these guidelines in more detail.

### Use Separated Presentation Patterns to Maximize the Amount of Shared Code

Sharing view-code across platforms can be difficult. Sharing presentation and business logic is easier if you separate this logic from the UI logic. Additionally, this makes your code easier to understand and maintain.

### Write Code So It Compiles on Both Platforms

Where possible, write your application code so that it compiles on both platforms to enable reuse. When this approach becomes too complicated, you have to make the tradeoff to see if the cost of having two codebases is less than having a less elegant solution. For example, in Silverlight you can execute the following LINQ expression against the **Items** property of an **ItemsControl**.

```C#
    ItemsControl someItemsControl = new ItemsControl();
    someItemsControl.Items.Add(new TextBox());
    bool hasDependencyObjects = someItemsControl.Items.Any(item => item is DependencyObject);
```

However, because the **Items** property is not **IEnumerable&lt;T&gt;** in WPF, this preferred approach does not work. Instead of creating a different version for WPF and Silverlight, opt for a less-preferred but single source solution, as shown in the following code.

```C#
    ItemsControl someItemsControl = new ItemsControl();
    someItemsControl.Items.Add(new TextBox());
    bool hasDependencyObjects = false;
    foreach (var item in someItemsControl.Items)
    {
        if (item is DependencyObject)
        {
            hasDependencyObjects = true;
            break;
        }
    }
```

The easiest approach is to begin writing your code in Silverlight, because it is a more constrained version of the .NET Framework.

#### Use \#if Statements If You Have Simple or Single Line Constructs

Sometimes it is not possible to create a single code base because of incompatibility between WPF and Silverlight. In this case, you can use \#if SILVERLIGHT constructs to create conditional compiled sections. The following code example shows a \#if SILVERLIGHT statement.

```C#
    #if SILVERLIGHT
                System.Windows.Application.Current.RootVisual = shell;
    #else
                Application.Current.MainWindow = shell;
                shell.Show();
    #endif
```

However, \#if statements have several drawbacks:

-   The code is less readable and maintainable. If code is scattered with \#if constructs, it becomes hard to read and a lot harder to maintain.
-   Debugging becomes harder. If there is a compiler error within a construct, when you try to open the file, Visual Studio selects the solution that has the physical file instead of the solution that has the error. This means you either have to manually close the file and open the correct solution or edit the code without IntelliSense.

#### Use Partial Classes When Most of the Class Is Similar but Some Methods Have Platform-Specific Implementations

When the changes between Silverlight and WPF become more complex, you can create partial classes. Mark the shared class files as **partial** and then create a partial class for the specific platforms. This also applies to unit tests. Below are some additional recommendations:

-   Try to keep the platform-specific methods private. This way, the unit tests will not need to contain specific logic for specific platforms.
-   Make sure your class has a single, clear responsibility. Any partial methods for platform-specific code should only change the implementation details.

**Note:** If the differences between the two platforms become very extensive, and the classes for both platforms become very different, consider creating platform-specific classes instead of partial class.

The following code example shows a shared partial class, **RealEstateService**, that is shared between the Silverlight and WPF projects in the Multi-Targeting QuickStart.

```C#
    // RealEstateService.cs
    namespace RealEstateListingViewer.Services
    {
        public partial class RealEstateService: IRealEstateService
        {
            public RealEstate GetRealEstate ()
            {
                ...
                return property;
            }

        }
```

The following code example shows the Silverlight-specific partial class for retrieving images for the **RealEstateService** class in the Multi-Targeting QuickStart.

```C#
    // RealEstateService.silverlight.cs
    namespace RealEstateListingViewer.Services
    {
        public partial class RealEstateService
        {
            /// <summary>
            /// Return the images. In Silverlight, you want to download the image
            /// from a web server.
            /// You can either store the images on the server or build an
            /// HTTP handler to retrieve the images. 
            /// </summary>
            private static BitmapImage GetImage()
            {
                Uri imageUri;
                Uri source = App.Current.Host.Source;

                if (source.ToString().StartsWith("file://", StringComparison.OrdinalIgnoreCase))
                {
                    imageUri = new Uri("../Images/House.jpg", UriKind.Relative);
                }
                else
                {
                    source = new Uri(string.Format(CultureInfo.InvariantCulture, "{0}://{1}:{2}/", source.Scheme, source.Host, source.Port));
                    imageUri = new Uri(source, "Images/house.jpg");
                }
                return new BitmapImage(imageUri);
            }
        }
    }
```

The following code example shows the WPF-specific partial class for retrieving images for the **RealEstateService** class in the Multi-Targeting QuickStart.

```C#
    // RealEstateService.WPF.cs
    namespace RealEstateListingViewer.Services
    {
        public partial class RealEstateService
        {
            /// <summary>
            /// Return the images. In a windows application, normally you
            /// retrieve the image from a database.
            /// But for simplicity, it is just being retrieved from the file system.
            /// </summary>
            private static BitmapImage GetImage()
            {
                return new BitmapImage(new Uri("../Images/house.jpg", UriKind.Relative));
            }
        }
    }
```

#### Use Partial Methods Only if You Need to Call an Extra Method on One Platform but Not the Other

If some work needs to be performed only in either Silverlight or WPF, you could also use partial methods. This means you can put an interface for the method in the parent class and put an implementation of that interface in only one of the platform-specific classes. For the other platform, the compiler will remove the method call. There are several limitations to partial methods:

-   Partial method declarations must begin with the contextual keyword **partial** and the method must return **void**.
-   Partial methods can have **ref** parameters but not **out** parameters.
-   Partial methods are implicitly **private**; therefore, they cannot be **virtual**.
-   Partial methods cannot be **extern**, because the presence of the body determines whether they are defining or implementing.
-   Partial methods can have **static** and **unsafe** modifiers.
-   Partial methods can be generic. Constraints are put on the defining partial method declaration and may optionally be repeated on the implementing one. Parameter and type parameter names do not have to be the same in the implementing declaration as in the defining one.
-   You cannot make a **delegate** to a partial method.

#### Build Platform-Specific Classes with a Single Responsibility

Frequently, it makes more sense to factor all platform-specific code into a separate class (for example, services or service agents). This can happen if most of the logic differs between the platforms. This way, you can create platform-specific implementations for services, such as caching, data access, or authentication. This approach also works for providing functionality that is only present in one platform. The following are some additional recommendations:

-   Use a common interface to share code between the different platforms. For example, in the Prism Library, there are several platform specific classes for loading module types, such as the **XapModuleTypeLoader** for Silverlight and the **FileModuleTypeLoader** for desktop applications. They both implement the **IModuleTypeLoader** interface.
-   When there is some shared functionality between the different platforms, favor composition over inheritance (for example, using the strategy pattern). In other words, see if it makes sense to factor out the shared code in a shared class with a specific responsibility. In some scenarios, inheritance makes sense.

### Create a Solution Folder for Silverlight and Another for WPF

Use solution folders to keep your solution organized. Typically, you do this by using two solution folders, one for the Silverlight code and the other for WPF code. For an example of how to structure your solution, see the Multi-Targeting QuickStart.

### Check Silverlight and WPF References When Refactoring Code

Sometimes a Silverlight reference might slip into a WPF project or vice versa. This is caused by using refactoring tools. If you get unexpected compiler errors about Silverlight assemblies not being referenced in your WPF project, check the references.

## Process Guidelines

Process guidelines include the following:

-   Develop the core application in Silverlight.
-   Link the shared code between the source project and the target project.
-   Use the same namespace for Silverlight and WPF projects.

The next sections describe each of these guidelines in more detail.

### Develop the Core Application in Silverlight

Because Silverlight is a subset of WPF, the same code will work on WPF without major modifications, so you should develop your core application in Silverlight.

### Link the Shared Code Between the Source Project and the Target Project

For files that are common to both Silverlight and WPF but need different references, you should link the files. One of the ways to do this is to use the Project Linker tool to link the shared code between the source project and the target project.

### Use the Same Namespace for Silverlight and WPF Projects

Keep the namespaces the same between projects because the shared code requires the same namespace.

## Team Build Guidelines

This section describes Team Build guidelines.

### Configure Team Build to Build in Place

If you use Team Build to build a solution that holds both WPF and Silverlight projects, you might run into file collision problems. By default, Team Build will copy the output from the projects to a single output folder. Because the output of the WPF and Silverlight projects should have the same name, there is a file name collision problem that will prevent you from compiling the projects or running unit tests.

By setting the property **CustomizableOutDir** to **true**, you are telling Team Build to build in place instead of copying the output to a single location. This prevents the collision name problem.

Additionally, if you set this property and want to run unit tests in your build, you also need to specify where the **TestContainers** are located.

```XML
    <PropertyGroup>
    <!Build in place>
        <CustomizableOutDir>true</CustomizableOutDir>
    </PropertyGroup>

      <!—Override the BeforeTestConfiguration target to specify where the testcontainers live. >
      <Target Name="BeforeTestConfiguration">

        <!
          Change the outdir, because the testtoolstask needs this to execute all the tests
        >
        <PropertyGroup>      <OutDir>$(SolutionRoot)\Source\</OutDir>    </PropertyGroup>

        <!Create a list of all tests dll's to run (test only the desktop versions) >
        <CreateItem Include="$(SolutionRoot)\**\Desktop\**\Bin\Debug\%2a.Tests.dll">      <Output ItemName="TestContainer" TaskParameter="Include" />    </CreateItem>

      </Target>
```

**Note:** This example assumes that your desktop projects are located in a folder named Desktop. MSTest.exe is only able to run unit tests that are targeting the desktop version of the .NET Framework, so Silverlight test assemblies are excluded.


## Contrasting Silverlight and WPF

Silverlight and WPF both allow you to develop rich user experiences based on XAML and the .NET Framework. However, there are some differences between these platforms, and these differences have to be carefully considered when transitioning an application between Silverlight and WPF or when building an application that targets both WPF and Silverlight.

**Note:** This topic describes differences between Silverlight 4 and WPF that is part of the .NET Framework 4.0. These differences are expected to be reduced in future versions of Silverlight and WPF.

## Silverlight and WPF Architectural Overview

WPF provides developers with a unified programming model for building rich Windows applications that incorporate UI, media, and documents. WPF enables software developers to deliver a new level of "user experience" (UX) by providing a declarative-based language (XAML) for specifying vector-based graphics that can scale and take advantage of hardware acceleration.

Silverlight is a cross-browser, cross-platform implementation of the .NET Framework for delivering next-generation rich interactive media and content over the web, desktop business applications, and browser-hosted Rich Internet Applications (RIAs) that can integrate data and services from many sources. Silverlight enables developers to build applications that significantly enhance the typical end user experience, compared with traditional web applications. Like WPF, Silverlight provides a XAML-based language to specify user interfaces.

Silverlight and WPF share many of the same features and capabilities, but they are built on top of different run-time stacks, as illustrated in the following image. WPF leverages the full .NET Framework and executes on the common language runtime (CLR). Silverlight is based on a subset of XAML and the full .NET Framework, and it executes on a different version of the CLR.

![](https://msdn.microsoft.com/en-us/Ff921109.36CE2C87819AC8C49B86F0E4F783E65B(en-us,PandP.40).png "WPF and Silverlight")

WPF and Silverlight

## Differences Between Silverlight and WPF

To keep Silverlight small and lightweight, some WPF and .NET Framework features are not available in Silverlight. Because of this, there can be subtle—and not so subtle—differences that have to be carefully considered when moving an application between Silverlight and WPF or when building an application that targets both WPF and Silverlight. This section describes some of the major differences the patterns & practices team encountered during Prism development. These differences relate to Silverlight 4 and WPF 4.0, the current versions at the time of this writing.

### Resources

Resources are simple collections of key-value pairs that can store almost any element (strings, brushes, styles, data sources, and many others). Resources can be associated with almost any element class that exposes a **Resources** property of type **ResourceDictionary**. The following are the main differences between Silverlight and WPF concerning resources:

-   Resources can contain static or dynamic content. Dynamic content can be changed at any time and consumers of the resource will be automatically updated. Dynamic resource references are not supported in Silverlight; therefore, only static resource references are available.

### Triggers

Triggers allow designers to define the visual behavior of a control by declaratively specifying how its properties change in response to events or property changes, such as highlighting a button when it is clicked. Typically, triggers are fired when a property of a control changes and results in one or more other properties of that control also changing. Triggers are defined inside a style and can be applied to any object of the specified target type.

Silverlight does not support triggers in **Styles**, **ControlTemplates**, or **DataTemplates** (the **Triggers** collection does not exist on these elements). However, similar behavior can be achieved by using the Silverlight Visual State Manager (VSM) to define interactive control templates. Using VSM, the visual behavior of a control, including any animations and transitions, are defined in the control template. This can be easily done by using Expression Blend 4. However, be aware that the XAML file will get more complex and that control templates built for Silverlight are not yet compatible with WPF.

The Expression Blend SDK provides Expression Blend behaviors for animation and visual state management that can be used to apply a consist look and feel between WPF and Silverlight UIs.

### Data Binding

Both WPF and Silverlight provide data binding support. The following are the main differences between Silverlight and WPF data binding:

-   In Silverlight, there is no **OneWayToSource** data flow mode.
-   In Silverlight, you cannot bind directly to XML data. A possible workaround for this is to convert the XML to CLR objects, and then bind to the CLR object.
-   In Silverlight, there is no **XMLDataProvider** class.
-   In Silverlight, there is no **DataTemplateSelector** class. In WPF, this class provides a way to choose a **DataTemplate** based on the data object and the data-bound element. However, to help support certain MVVM scenarios, Prism offers similar functionality for Silverlight in its **DataTemplateSelector** class.

### Commanding

The following are the differences between Silverlight and WPF regarding commanding:

-   Routed commands are not available in Silverlight. However, the **ICommand** interface is available in Silverlight, allowing developers to create their own custom commands. The Prism Library provides the **DelegateCommand** and **CompositeCommand** classes to simplify command implementation.
-   In WPF, controls can be hooked up to commands through their **Command** property. By doing this, developers can declaratively associate controls and commands. This also means a control can interact with a command so that it can invoke the command and have its enabled status automatically updated. In Silverlight, several controls support the **Command** property, but not as many as in WPF. For Silverlight controls that do not offer **Command** properties, consider using Expression Blend behaviors to invoke the command based on triggers.
-   There is no input gesture or input binding support in Silverlight.

### Miscellaneous

The following are some miscellaneous differences between Silverlight and WPF:

-   In Silverlight, the **UIElement** class has an internal constructor; therefore, you cannot create a control inheriting from it.
-   In Silverlight, there is no **x:Type** markup extension support or support for custom markup extensions.
-   In Silverlight, there is no **x:Static** markup extension support or support for custom markup extensions. In Silverlight, items added to a **TabControl** control are not automatically wrapped inside a **TabItem** type, as is the case with WPF.
-   All Silverlight network calls must be asynchronous.
-   Silverlight networking, except for trusted out-of-browser applications, respect server-client access policies for servers outside the site of origin.

## More Information

You can download [Project Linker](http://visualstudiogallery.msdn.microsoft.com/en-us/5e730577-d11c-4f2e-8e2b-cbb87f76c044) from Visual Studio Gallery or open Visual Studio, click on **Tools**, point to **Extension Manager**, click on **Online Gallery**, and search for "Project Linker."

For more information about structuring your assemblies to take advantage of the binary compatibility support between Silverlight and WPF, see the CLR Team Blog post, [Sharing Silverlight Assemblies with .NET Apps](http://blogs.msdn.com/b/clrteam/archive/2009/12/01/sharing-silverlight-assemblies-with-net-apps.aspx).

For more information about WPF architecture, see [WPF Architecture](http://msdn.microsoft.com/en-us/library/ms750441.aspx) on MSDN.

For more information about Silverlight architecture, see [Silverlight Architecture](http://msdn.microsoft.com/en-us/library/bb404713(vs.95).aspx) on MSDN.

For a summary of the differences between WPF and Silverlight, see [WPF Compatibility](http://msdn.microsoft.com/en-us/library/cc903925(vs.95).aspx) on MSDN.

For more information about the Visual State Manager and how it works in creating controls, see the following articles about creating customizable controls on MSDN:

-   For Silverlight: [Creating a New Control by Creating a ControlTemplate](http://msdn.microsoft.com/en-us/library/cc278064(vs.95).aspx).
-   For WPF in .NET Framework: [Creating a Control That Has a Customizable Appearance](http://msdn.microsoft.com/en-us/library/ee330302.aspx).

For more information about creating an application with elevated trust, see [Trusted Applications](http://msdn.microsoft.com/en-us/library/ee721083(vs.95).aspx) on MSDN.

