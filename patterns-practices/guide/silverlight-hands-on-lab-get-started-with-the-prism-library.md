---
TOCTitle: 'Silverlight Hands-On Lab: Get Started with the Prism Library'
Title: 'Silverlight Hands-On Lab: Get Started with the Prism Library'
ms:assetid: 'daa3c050-e4e5-4c90-8905-9d38a0066b15'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Ff921096(v=PandP.40)'
---

# Silverlight Hands-On Lab: Get Started with the Prism Library


In this lab, you will learn the basic concepts of Prism and apply them to create a Prism solution that you can use as the starting point for building a composite Silverlight application. After completing this lab, you will be able to do the following:

-   You will create a new solution based on the Prism Library.
-   You will create and load a module.
-   You will create a view and show it in the shell window.

## Preparation

This topic requires you to have the following Prism Library and Unity Application Block assemblies:

-   **Microsoft.Practices.Prism.dll**
-   **Microsoft.Practices.Prism.UnityExtensions.dll**
-   **Microsoft.Practices.ServiceLocation.dll**
-   **Microsoft.Practices.Unity.Silverlight.dll**

These assemblies are included with the Prism download in the \\bin folder where you extracted Prism.

> [!NOTE]
> This hands-on lab uses the Unity container, but you can also use the Managed Extensibility Framework (MEF) with the Prism Library.

This hands-on lab assumes that you understand Prism basic concepts. For more information, see "Prism Key Concepts" in "Introduction" in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

## Procedures

This lab includes the following tasks:

-   Task 1: Creating a Solution Using the Prism Library
-   Task 2: Adding a Module
-   Task 3: Adding a View

The next sections describe each of these tasks.

> [!NOTE]
> The instructions of this hands-on lab are based on the HelloWorld solution. To open the solution in Visual Studio, run the file Silverlight only - Open QS - Hello World QuickStart.bat.

## Task 1: Creating a Solution Using the Prism Library

In this task, you will create a solution using the Prism Library. You will be able to use this solution as a starting point for your composite Silverlight application. The solution includes recommended practices and techniques and is the basis for the procedures in Prism. To create a solution with the Prism Library, the following tasks must be performed:

1.  **Create a solution with a shell project**. In this task, you create the initial Visual Studio solution and add a Silverlight Application project that is the basis of solutions built using the Prism Library. This project is known as the shell project.
2.  **Set up the shell project**. In this task, you set up a user control, the shell user control, to host different user interface (UI) components in a decoupled way.
3.  **Set up the application's bootstrapper**. In this task, you set up code that initializes the application.

The following procedure describes how to create a solution with a shell project. A shell project is the basis of a typical application built using the Prism Library—it is a Silverlight Application project that contains the application's startup code, known as the bootstrapper, and a main window where views are typically displayed (the shell window).

**To create a solution with a shell project**

1.  In Visual Studio, create a new Silverlight application. To do this, point to **New** on the **File** menu, and then click **Project**. In the **Project types** list, click **Silverlight** in the **Visual C#** node. In the **Templates** box, click **Silverlight Application**. Finally, set the project's name to **HelloWorld.Silverlight**, specify a valid location, and then click **OK**.
2.  On the **New Silverlight Application** dialog box, make sure the **Host the Silverlight application in a new Web site** option is selected, and then click **OK**.

    Visual Studio will create the HelloWorld.Silverlight project and the HelloWorld.Silverlight.Web ASP.NET web application project, as shown in the following illustration. The first project will be the shell project of your application and the second will be a web project that will host the Silverlight application.

    ![](https://msdn.microsoft.com/en-us/Ff921096.C1BC76C91E1D2D734B4CCAED93DC37EC(en-us,PandP.40).png "HelloWorld project")

    HelloWorld project

3.  Using Windows Explorer, create a folder named Library.Silverlight inside your solution's folder, and then copy the following assemblies into it (they are located in the Source\\bin\\Silverlight folder):
    -   **Microsoft.Practices.Prism.dll**. This assembly contains the implementation of the Prism Library core components, such as modularity, logging services, communication services, and definitions for several core interfaces. It also contains the implementation of the Prism Library components that target Silverlight applications, including commands, regions, and events.
    -   **Microsoft.Practices.Prism.UnityExtensions.dll**. This assembly contains base and utility classes you can reuse in applications built with the Prism Library that consume the [Unity Application Block](http://www.msdn.com/unity). For example, it contains a bootstrapper base class, the **UnityBootstrapper** class, that creates and configures a Unity container with default Prism Library services when the application starts.
    -   **Microsoft.Practices.Unity.Silverlight.dll**. This assembly enables you to use the Unity Application Block in your application. By default, applications built using Prism use the Unity Application Block. However, developers who prefer to use different container implementations can build adapters for them using the provided extensibility points in the Prism Library.
    -   **Microsoft.Practices.ServiceLocation.dll**. This assembly contains the Common Service Locator interface used by Prism to provide an abstraction over Inversion of Control (IoC) containers and service locators; therefore, you can change the container implementation with ease.
4.  In the HelloWorld.Silverlight project, add references to the assemblies mentioned in the previous step. To do this, right-click the HelloWorld.Silverlight project in Solution Explorer, click **Add Reference**, click **Browse** in the **Add Reference** dialog box, browse to and select the assemblies you want to add, and then click **OK**.

> [!NOTE]
> For IntelliSense to be available for the Prism Library, the XML documentation files for each of these assemblies must be placed in the same directory as the referenced assemblies.

The shell user control is the top-level user control of an application based on the Prism Library. This user control is a place to host different UI components that exposes a way for itself to be dynamically populated by others, and it may also contain common UI elements, such as menus and toolbars. The shell user control sets the overall appearance of the application.

The following procedure explains how to set up the shell.

**To set up the shell**

1.  In Solution Explorer, rename the file MainPage.xaml to Shell.xaml.
2.  Open the code-behind file Shell.xaml.cs and rename the **MainPage** class to **Shell** using the Visual Studio refactoring tools. To do this, right-click **MainPage** in the class signature, point to **Refactor**, and then click **Rename**, as shown in the following illustration. In the **Rename** dialog box, type **Shell** as the new name, and then click **OK**. If the **Preview Changes – Rename** dialog box appears, click **Apply**.

    ![](https://msdn.microsoft.com/en-us/Ff921096.7570EB488C758FE61CDF76BD15A3326F(en-us,PandP.40).png "Page renaming using Visual Studio refactoring tools")

    Page renaming using Visual Studio refactoring tools

3.  In XAML view, open the Shell.xaml file, and then set the following attribute value to the **UserControl** root element:

    -   x:Class = "HelloWorld.Silverlight.Shell" (this matches the code-behind class's name)

    Your code should look like the following.

    ```XAML	
            <UserControl x:Class="HelloWorld.Silverlight.Shell"
                xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation" 
                xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml" 
                Width="400" Height="300">
                <Grid x:Name="LayoutRoot" Background="White">

                </Grid>
            </UserControl>
    ```

## Regions

The following procedure describes how to add an **ItemsControl** control to the shell control and associate a region to it. In a subsequent task, you will dynamically add a view to this region.

**To add a region to the shell**

1.  In the Shell.xaml file, add the following namespace definition to the root **UserControl** element. You need this namespace to use an attached property for regions that is defined in the Prism Library.

    ```XAML
            xmlns:Regions="http://www.codeplex.com/prism"
    ```

2.  Replace the **Grid** control in the shell user control with an **ItemsControl** control named **MainRegion**, as shown in the following code.

    ```XAML
            <UserControl x:Class="HelloWorld.Silverlight.Shell"
                xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation" 
                xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
                        xmlns:Regions="http://www.codeplex.com/prism"
                        Width="400" Height="300">
                <ItemsControl Name="MainRegion"/>
            </UserControl>
    ```

3.  In the **ItemsControl** control definition, set the attached property **Regions:RegionManager.RegionName** to "MainRegion", as shown in the following code. This attached property indicates that a region named MainRegion is associated to the control.

    ```XAML
            <ItemsControl Name="MainRegion" Regions:RegionManager.RegionName="MainRegion"/>
    ```

> [!NOTE]
> When the shell is instantiated, Silverlight resolves the value of the **Regions:RegionManager.RegionName** attached property and invokes a callback in the **RegionManager** class. This callback creates a region and associates it with the **ItemsControl** control.

## Bootstrapper

The bootstrapper is responsible for the initialization of an application built using the Prism Library. The Prism Library includes **UnityBootstrapper** and **MefBootstrapper** classes, which implement most of the functionality necessary to use either Unity or MEF as the container in your application. If you are using a container other than Unity, you should write your own container-specific bootstrapper.

The following procedure explains how to set up the application's bootstrapper.

**To set up the application's bootstrapper**

1.  Add a new class file named Bootstrapper.cs to the HelloWorld.Silverlight project.
2.  Add the following **using** statements at the top of the file. You will use them to refer to elements referenced in the **UnityBootstrapper** class.

    ```C#
            using Microsoft.Practices.Prism.Modularity;
            using Microsoft.Practices.Prism.UnityExtensions;
            using Microsoft.Practices.Unity;
    ```

3.  Update the signature of the **Bootstrapper** class to inherit from the **UnityBootstrapper** class.

    ```C#
            class Bootstrapper : UnityBootstrapper
            {
            }
    ```
4.  Override the **CreateShell** method in the **Bootstrapper** class. In this method, create an instance of the shell window, and return it, as shown in the following code.

    ```C#
            protected override DependencyObject CreateShell()
            {
                return Container.Resolve<Shell>();
            }
    ```
> [!NOTE]
> You return the shell object to have the **UnityBootstrapper** base class attach an instance of the region manager service to it. The region manager service is a service included in the Prism Library that manages regions in the application. By having a region manager instance attached to the shell window, you can declaratively register regions from XAML code that will exist in the scope of the shell window and child views.

5.  Override the **InitializeShell** method in the **Bootstrapper** class. In this method, display the shell to the user.

    ```C#
            protected override void InitializeShell()
            {
                base.InitializeShell();
                Application.Current.RootVisual = (UIElement)this.Shell;
            }
    ```

6.  Override the **ConfigureModuleCatalog** method. In this template method, you populate the module catalog with modules. The module catalog interface is **Microsoft.Practices.Prism.Modularity.IModuleCatalog**, and it contains metadata for all the modules in the application. Because the application contains no modules at this point, the implementation of the **ConfigureModuleCatalog** method should simply call the base implementation and return. You can paste the following code in your **Bootstrapper** class to implement the method.

    ```C#
            protected override void ConfigureModuleCatalog()
            {
                base.ConfigureModuleCatalog();
            }
    ```

    For more information about module loading and module catalogs, see [Task 2: Adding a Module](#task2addingmodule) later in this topic.

7.  Open the file App.xaml.cs, and then replace the **Application\_Startup** event handler with the following code to initialize the bootstrapper when the application starts.

    ```C#
            private void Application_Startup(object sender, StartupEventArgs e)
            {
                Bootstrapper bootstrapper= new Bootstrapper();
                bootstrapper.Run();
            }
    ```

8.  Build and run the application. You should see an empty Hello World window, as shown in the following illustration.

    ![](https://msdn.microsoft.com/en-us/Ff921096.D39B06AF800B3B4FD69D71B1E3587DDB(en-us,PandP.40).png "Hello World window")

    Hello World window

## Task 2: Adding a Module

In this task, you will create a module and add it to your solution. A module in Prism is a logical unit in your application. Adding a module to your solution involves the following tasks:

1.  **Creating a module**. In this task, you create a module project with a module initializer class.
2.  **Configuring how the module is loaded**. In this task, you configure your application to load the module.

The following procedure describes how to create a module.

**To create a module**

1.  Add a new Silverlight class library project to your solution. To do this, right-click the **HelloWorld.Silverlight** solution node in Solution Explorer, point to **Add**, and then click **New Project**. In the **Project types** list, select **Silverlight** in the **Visual C#** node. In the **Templates** box, click **Silverlight Class Library**. Finally, set the project's name to HelloWorldModule, and then click **OK**. The following illustration shows your solution.

    ![](https://msdn.microsoft.com/en-us/Ff921096.6DA907DFDC988B772825C9946460C930(en-us,PandP.40).png "Solution with a module named HelloWorldModule")

    Solution with a module named HelloWorldModule

2.  Add references in your module to the following Prism Library assemblies. To do this, right-click the **HelloWorldModule** project in Solution Explorer, and then click **Add Reference**. In the **Add Reference** dialog box, click the **Browse** tab, click the following assemblies, and then click **OK**:
    -   **Microsoft.Practices.Prism.dll**
3.  Rename the Class1.cs file to HelloWorldModule.cs. To do this, right-click the file in Solution Explorer, click **Rename**, set the new name, and then press ENTER. In the dialog box that asks if you want to perform a rename of all references to your class, click **Yes**.
4.  Open the file HelloWorldModule.cs and add the following **using** statement at the top. You will use it to refer to modularity elements provided by the Prism Library.

    ```C#
            using Microsoft.Practices.Prism.Modularity;
    ```

5.  Change the class signature to implement the **IModule** interface, as shown in the following code.
    ```C#
        public class HelloWorldModule : IModule
        {
        }
    ```

6.  In the **HelloWorldModule** class, add an empty definition of the **Initialize** method, as shown in the following code.

    ```C#
            public void Initialize()
            {

            }
    ```

7.  Add a Views folder to the HelloWorldModule project. In this folder, you will store your view implementations. To do this, right-click the **HelloWorldModule** project in Solution Explorer, point to **Add**, and then click **New Folder**. Change the folder name to Views.

    This step is recommended to organize your projects; this is useful when a module contains several artifacts. The following are other common folders that you can add to your module:

    -   **Services**. In this folder, you store service implementations and service interfaces.
    -   **Controllers**. In this folder, you store controllers.

    The following illustration shows the solution with the **HelloWorldModule** module.

    ![](https://msdn.microsoft.com/en-us/Ff921096.219DB15C65918EF2DEFA61278763BD5F(en-us,PandP.40).png "Solution with the HelloWorldModule")

    Solution with the HelloWorldModule

8.  Build the solution.

At this point, you have a solution based on the Prism Library with a module. However, the module is not being loaded into the application. The following section describes module loading and how you can load modules with the Prism Library.

## Modules in the Application Life Cycle

Modules go through a three-step process during the application life cycle:

1.  Modules are discovered by the module catalog. The module catalog contains a collection of metadata about those modules. This metadata can be consumed by the module manager service.
2.  The module manager service coordinates the modules initialization. It manages the retrieval and the subsequent initialization of the modules. It loads modules—retrieving them if necessary—and validates them.
3.  Finally, the module manager instantiates the module initializer class of each module and invokes the **Initialize** method on them.

### Populating the Module Catalog

The Prism Library provides several ways to populate the module catalog. In Silverlight, you can populate the module catalog from code or from a XAML file. The following procedure explains how to populate the catalog from code to load the **HelloWorldModule** module into the HelloWorld.Silverlight application.

**To populate the module catalog with the HelloWorld module from code**

1.  In your shell project, add a reference to the module project. To do this in Solution Explorer, right-click the **HelloWorld.Silverlight** project, and then click **Add Reference**. In the **Add Reference** dialog box, click the **Projects** tab, click the **HelloWorldModule** project, and then click **OK**.
2.  Open the Bootstrapper.cs file and explore the **ConfigureModuleCatalog** method. The method implementation is shown in the following code.

    ```C#
            protected override void ConfigureModuleCatalog()
            {
                base.ConfigureModuleCatalog();
            }
    ```

    The **ModuleCatalog** class is used to define the application's modules from code—it implements the methods included in the **IModuleCatalog** interface and adds an **AddModule** method for developers to manually register modules that should be loaded in the application. The signature of this method is shown in the following code.

    ```C#	
            public ModuleCatalog AddModule(Type moduleType, InitializationMode initializationMode, params string[] dependsOn)
    ```

    The **AddModule** method returns the same module catalog instance and takes the following parameters:

    -   **The module initializer class's type of module to load**. This type must implement the **IModule** interface.
    -   **The Initialization mode**. This parameter indicates how the module will be initialized. The possible values are **InitializationMode.WhenAvailable** and **InitializationMode.OnDemand**.
    -   **An array containing the names of the modules that the module depends on, if any**. These modules will be loaded before your module to ensure your module dependencies are available when it is loaded.

3.  Update the **ConfigureModuleCatalog** method to register the **HelloWorldModule** module with the module catalog instance. To do this, you can replace the **ConfigureModuleCatalog** implementation with the following code.

    ```C#
            protected override void ConfigureModuleCatalog()
            {
                base.ConfigureModuleCatalog();

                ModuleCatalog moduleCatalog = (ModuleCatalog)this.ModuleCatalog;
                moduleCatalog.AddModule(typeof(HelloWorldModule.HelloWorldModule));
            }
    ```

    > [!NOTE]
> In this example, the modules are directly referenced by the shell. That is why this example is able to use **typeof(Module)** to add modules to the catalog. But keep in mind that modules whose type is not already available can also be added to the catalog.<br />The **WhenAvailable** initialization mode is the default value if no initialization mode is specified.

4.  Build and run the solution. To verify that the **HelloWorldModule** module gets initialized, add a breakpoint to the **Initialize** method of the **HelloWorldModule** class. The breakpoint should be hit when the application starts.

## Task 3: Adding a View

In this task, you will create and add a view to the **HelloWorldModule** module. Views are objects that contain visual content. Views are often user controls. Adding a view to your module involves the following tasks:

1.  **Creating the view**. In this task, you implement the view by creating the visual content and writing code to manage the UI elements in the view.
2.  **Showing the view in a region**. In this task, you obtain a reference to a region and add the view to it.

The following procedure describes how to create a view.

**To create a view**

1.  Add a new Silverlight user control to your module. To do this, right-click the Views folder in Solution Explorer, point to **Add**, and then click **New Item**. In the **Add New Item** dialog box, select the **Silverlight User Control** template, set the name to **HelloWorldView.xaml**, and then click **Add**.
2.  Add a "Hello World" text block to the view. To do this, you can replace your code in the file HelloWorldView.xaml with the following code.

    ```XAML
            <UserControl x:Class="HelloWorldModule.Views.HelloWorldView"
                xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
                xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml">
                <Grid x:Name="LayoutRoot" Background="White">
                    <TextBlock Text="Hello World" Foreground="Green" HorizontalAlignment="Center" VerticalAlignment="Center" FontFamily="Calibri" FontSize="24" FontWeight="Bold"></TextBlock>
                </Grid>
            </UserControl>
    ```

3.  Save the file.

> [!NOTE]
> To keep this hands-on lab simple, the procedure did not explain how to create a view following the Model-View-ViewModel (MVVM) pattern. For more information about the MVVM pattern, see "[Implementing the MVVM Pattern](https://msdn.microsoft.com/en-us/library/gg405484(v=pandp.40))."

## Region Manager

The region manager service is responsible for maintaining a collection of regions and creating new regions for controls. This service implements the **Microsoft.Practices.Prism.Regions.IRegionManager** interface. Typically, you interact directly with this service to locate regions in a decoupled way through their name and add views those regions. By default, the **UnityBootstrapper** base class registers an instance of this service in the application container. This means that you can obtain a reference to the region manager service in the HelloWorld application by using dependency injection. The following procedure explains how to obtain an instance of the region manager and add the HelloWorldView view to the shell's main region.

**To show the view in the shell**

1.  Open the HelloWorldModule.cs file.
2.  Add the following **using** statement to the top of the file. You will use it to refer to the region elements in the Prism Library.

    ```C#
            using Microsoft.Practices.Prism.Regions;
    ```

3.  Create a private read-only instance variable to hold a reference to the region manager. To do this, paste the following code inside the class body.

    ```C#
            private readonly IRegionManager regionManager;
    ```

4.  Add the constructor of the **HelloWorldModule** class to obtain a region manager instance through constructor dependency injection and store it in the **regionManager** instance variable. To do this, the constructor has to take a parameter of type **Microsoft.Practices.Prism.Regions.IRegionManager**. You can paste the following code inside the class body to implement the constructor.

    ```C#
            public HelloWorldModule(IRegionManager regionManager)
            {
            this.regionManager = regionManager;
            }
    ```

5.  In the **Initialize** method, invoke the **RegisterViewWithRegion** method on the **RegionManager** instance. This method registers a region name with its associated view type in the region view registry; the registry is responsible for registering and retrieving these mappings.

    The **RegisterViewWithRegion** method has two overloads. When you want to register a view directly, you use the first overload that requires two parameters, the region name and the type of the view. This is shown in the following code.

    ```C#
            public void Initialize()
            {
                regionManager.RegisterViewWithRegion("MainRegion", typeof(Views.HelloWorldView));
            }
    ```

    The UI composition approach used in the preceding code is known as view discovery. When using this approach, you specify the views and the region where the views will be loaded. When a region is created, it asks for its associated views and automatically loads them.

    > [!NOTE]
> The region's name must match the name defined in the **RegionName** attribute of the region.

6.  Build and run the application. You should see the Hello World window with a "Hello World" message, as shown in the following illustration.

    ![](https://msdn.microsoft.com/en-us/Ff921096.DDE026EF20F7DA3363249DD80152C593(en-us,PandP.40).png "Hello World message")

    Hello World message

> [!NOTE]
> To open the solution that results from performing the steps in this Hands-on Lab in Visual Studio, run the file Silverlight only - Open QS - Hello World QuickStart.

## More Information

To create a Hello World application using WPF, see "WPF Hands-On Lab: Get Started with the Prism Library" in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

To learn about other QuickStarts included with Prism, see the following topics in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580):

-   Modularity QuickStarts for WPF
-   [Modularity QuickStarts for Silverlight](https://msdn.microsoft.com/en-us/library/ff921163(v=pandp.40)) (also available on MSDN)
-   Basic MVVM QuickStart
-   MVVM QuickStart
-   Commanding QuickStart
-   UI Composition QuickStart
-   State-Based Navigation QuickStart
-   View-Switching Navigation QuickStart
-   Event Aggregation QuickStart
-   [Multi-Targeting QuickStart](https://msdn.microsoft.com/en-us/library/ff921176(v=pandp.40)) (also available on MSDN)

