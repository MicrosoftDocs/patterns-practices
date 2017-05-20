---
TOCTitle: Modularity QuickStarts for Silverlight
Title: Modularity QuickStarts for Silverlight
ms:assetid: 'af1ff7c8-dbb1-4ab8-b90f-328628a22bb3'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Ff921163(v=PandP.40)'
---

# Modularity QuickStarts for Silverlight

From: [Prism 4.1 - Developer's Guide to Microsoft Prism Library for WPF and Silverlight](https://msdn.microsoft.com/en-us/library/gg430869(v=pandp.40).aspx)

The QuickStarts included in this topic demonstrate how to code, discover, and initialize modules using Prism:

-   **Creating modules**. Modules are classes that implement the **IModule** interface. Declarative attributes can be used to name modules, control initialization, and define dependencies.
-   **Registering modules**. Modules can be registered in the following ways:
    -   **Directly in code**. Modules can be directly registered in the module catalog in the application code. Using this approach, you can use conditional logic to determine which module should be included in your application. Modules added in code are referenced by the application instead of being loaded at run time.
    -   **Using XAML**. Prism can register modules with the module catalog by loading an Extensible Application Markup Language (XAML) file. This is very similar to the configuration approach in the desktop scenarios. Declaring the modules in XAML allows the modules to be downloaded and initialized independent of the application XAP file.
-   **Registering module dependencies**. Modules can have dependencies on other modules. Prism provides dependencies management, including cyclic dependencies and duplicate module detection.
-   **Initializing modules**. There are two initialization modes supported in Prism. They are the following:
    -   **When available**. Modules can be initialized as soon as they are available. Modules downloaded with the application are initialized during startup. Modules set to download in the background are initialized immediately after downloading completes.
    -   **On-demand**. Modules can be initialized when the application code requests it. Modules downloaded in the background start downloading when the application requests the module, and then they initialize as soon as downloading completes.
-   **Downloading modules in the background**. Modules set to download in the background asynchronously download the associated XAP file and then load and initialize modules within the XAP. Prism prevents XAPs from being downloaded twice or multiple concurrent downloads of the same XAP. You can perform the following things when downloading modules in the background:

    -   **Displaying progress**. An application can subscribe to a progress-changed event to display byte count and percentage progress as modules are downloaded.
    -   **Action on download complete**. An application can subscribe to a load module–completed event to take additional action after a module loads and initializes.

    > [!NOTE]
> Creating and populating a **ModuleCatalog** in XAML and downloading XAP files are two different concepts that can be used independently of each other. You can create and populate your **ModuleCatalog**, even if you do not download your modules. It is possible to add a **ModuleInfo** from code, instead of XAML, that indicates a module should be downloaded in a XAP file.

-   **Leveraging different dependency injection containers**. Traditionally, QuickStarts have demonstrated using the Unity container, while the core library code remained container-agnostic. With the addition of Managed Extensibility Framework (MEF) to the .NET Framework 4, there are two QuickStarts, each of which uses a different container:
    -   **ModularityWithMef**. This QuickStart demonstrates modularity when using the MEF as the dependency injection container. Prism leverages MEF's declarative attribute model to integrate the **ModuleCatalog** and MEF's **ComposablePartsCatalog**.
    -   **ModularityWithUnity**. This QuickStart demonstrates modularity when using Unity as the dependency injection container.

## Scenarios

This section describes the scenarios included in both modularity QuickStarts. Each QuickStart is composed of six modules: ModuleA, ModuleB, ModuleC, ModuleD, ModuleE, and ModuleF. Each module demonstrates an aspect of how modules are discovered, downloaded, and initialized.

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Module</p></th>
<th><p>Defined in</p></th>
<th><p>Initialized</p></th>
<th><p>Downloaded</p></th>
<th><p>Depends on</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A</p></td>
<td><p>Code</p></td>
<td><p>When available</p></td>
<td><p>With application</p></td>
<td><p>D</p></td>
</tr>
<tr class="even">
<td><p>B</p></td>
<td><p>XAML</p></td>
<td><p>When available</p></td>
<td><p>In background</p></td>
<td><br />
</td>
</tr>
<tr class="odd">
<td><p>C</p></td>
<td><p>Code</p></td>
<td><p>On demand</p></td>
<td><p>With application</p></td>
<td><br />
</td>
</tr>
<tr class="even">
<td><p>D</p></td>
<td><p>XAML</p></td>
<td><p>When available</p></td>
<td><p>In background</p></td>
<td><br />
</td>
</tr>
<tr class="odd">
<td><p>E</p></td>
<td><p>XAML</p></td>
<td><p>On demand</p></td>
<td><p>In background</p></td>
<td><br />
</td>
</tr>
<tr class="even">
<td><p>F</p></td>
<td><p>XAML</p></td>
<td><p>On demand</p></td>
<td><p>In background</p></td>
<td><p>E</p></td>
</tr>
</tbody>
</table>

Each QuickStart displays each module as a control. The module control indicates whether it has been initialized, displays downloading progress, and on-demand modules can be clicked to request initialization. The control also provides a tooltip that shows its current initialization state and discovery information.

At the bottom of each QuickStart page is a text box that displays the log entries from the bootstrapping sequence and module-loading details.

The following illustration shows the main page of the Modularity with MEF QuickStart.

![](images/quickstart-silverlight-version-1(en-us,PandP.40).png "Modularity QuickStart user interface - Silverlight version")

Modularity QuickStart user interface - Silverlight version

## Building and Running the QuickStarts

This QuickStart requires Microsoft Visual Studio 2010. The Silverlight version of this QuickStart also requires [Silverlight 4](http://www.microsoft.com/silverlight/) and the [Silverlight 4 Tools for Visual Studio 2010](http://www.microsoft.com/downloads/en/details.aspx?familyid=b3deb194-ca86-4fb6-a716-b67c2604a139&displaylang=en).

**To build and run the ModularityWithMef QuickStart**

1.  In Visual Studio, open the solution file Quickstarts\\Modularity\\Silverlight\\ModularityWithMef\\ModularityWithMef.Silverlight.sln.
2.  Right-click the ModularityWithMef.Silverlight.Web project, and then click **Set as StartUp Project**.
3.  On the **Build** menu, click **Rebuild Solution**.
4.  Press F5 to run the QuickStart.

**To build and run the ModularityWithUnity QuickStart**

1.  In Visual Studio, open the solution file Quickstarts\\Modularity\\Silverlight\\ModularityWithUnity\\ModularityWithUnity.Silverlight.sln.
2.  Right-click the ModularityWithUnity.Silverlight.Web project, and then click **Set as StartUp Project**.
3.  On the **Build** menu, click **Rebuild Solution**.
4.  Press F5 to run the QuickStart.

> [!NOTE]
> It is not possible to start Silverlight project directly, without using the Silverlight.Web project. Normally, you can start Silverlight applications directly, without using a web application project. The Silverlight Application Project will then dynamically create a test page that will host the application. However, the Silverlight security model does not allow the downloading of modules when the application is hosted in a dynamically created test page.

## Walkthrough

To explore the scenario, perform the steps to build and run the QuickStart:

1.  The main window shows a set of modules, each of which displays the module's initialization state. As the application starts, Module B and Module D start downloading, as shown in the following illustration.

    ![](images/quickstart-silverlight-version-2(en-us,PandP.40).png "Main page of Modularity with MEF QuickStart – Silverlight version")

    Main page of Modularity with MEF QuickStart – Silverlight version

    Module B and D are initialized when they are available, and then they are downloaded in the background. The progress bars show each of these as they download. Module A is initialized when it is available, and it depends on Module D. Because Module D has not completed downloading, Module A is not yet initialized. The trace window at the bottom shows messages as the application is initialized.

    > [!NOTE]
> If no dependencies are specified, the module load order is non-deterministic.

2.  Hover over the Module A control. When the mouse hovers over the **Module A** control, a descriptive tooltip displays, as shown in the following illustration.

    ![](images/module-information-tooltip(en-us,PandP.40).png "Module information  tooltip")

    Module information tooltip

3.  As you hover the pointer over a module, a tooltip displays that shows information about its status, discovery, initialization, download timing, and dependencies.
4.  Click the **Module C** control. As each module initialization state changes, the visual control is updated. When the **Module C** control is clicked, Module C loads, as shown in the following illustration.

    ![](images/quickstart-silverlight-version-3(en-us,PandP.40).png "Screen shot of Module C loaded")

    Screen shot of Module C loaded

5.  Module B and Module D have downloaded and initialized. Module A also initialized right after its dependency, Module D, was initialized. Module C was clicked by the user. Because it was downloaded with the application, it is immediately initialized.
6.  Click the **Module F** control. When the Module F control is clicked, Module E and Module F load, as shown in the following illustration.

    ![](images/quickstart-silverlight-version-4(en-us,PandP.40).png "Screen shot of Module E getting loaded to load Module F")

    Screen shot of Module E getting loaded to load Module F

    Notice that Module F completes its download first, but it is not initialized until after Module E initializes because of the dependency. This QuickStart implements a delay download manager to simulate network latency when downloading some modules. In this case, Module E downloads much faster than Module F.

## Implementation Details

The QuickStarts highlight the key components in modularity. The following sections describe the key artifacts the QuickStarts.

The **Bootstrapper** overrides several methods from either the **MefBootstrapper** or the **UnityBootstrapper** to support the specifics of the application. These sections describe important differences between the dependency injection containers.

## Application Startup

The application uses the **Bootstrapper** to start the application and initialize the main page.

```C#
    private void Application_Startup(object sender, StartupEventArgs e)
    {
        // The bootstrapper will create the Shell instance, 
        // so we do not need to set the RootVisual.
        Bootstrapper bootstrapper = new Bootstrapper();
        bootstrapper.Run();
    }
```

The **Bootstrapper** overrides the **CreateShell** template method to set the RootVisual for the Silverlight application.

```C#
    protected override DependencyObject CreateShell()
    {
        Shell mainPage = new Shell();
        Application.Current.RootVisual = mainPage;
        return mainPage;
    }
```

## Creating Modules

In this QuickStart, six modules are created by implementing the **IModule** interface. Attributes are added, depending on the dependency injection container chosen (that is, Unity or MEF).

```C#
    // when using Unity
    public class ModuleA : IModule
    {
    }
```

When using Unity on the Silverlight platform, no attributes are required.

```C#
    // when using MEF
    [ModuleExport(typeof(ModuleA), DependsOnModuleNames = new string[] { "ModuleD" })]
    public class ModuleA : IModule
    {
        ...
    }
```

When using MEF, the **ModuleExport** attribute allows MEF to discover the appropriate type deriving from **IModule**; in addition, it provides the ability to specify additional module metadata.

## Registering Modules

In this QuickStart, some modules are directly referenced by the application and others are downloaded in the background and are referenced in the XAML file.

The **Bootstrapper** overrides the **CreateModuleCatalog** template method to register modules using a XAML file.

```C#
    protected override IModuleCatalog CreateModuleCatalog()
    {
        // Module B, D, E and F are defined in XAML.
        return Microsoft.Practices.Prism.Modularity.ModuleCatalog.CreateFromXaml(new Uri("/ModularityWithUnity.Silverlight;component/ModulesCatalog.xaml", UriKind.Relative));
    }
```

> [!NOTE]
> Managed Extensibility Framework (MEF) does not provide a mechanism for associating modules with the XAP file to download. Prism's **ModuleCatalog** continues to be used even when using the MEF container to support on-demand and background downloading.<br />
Behind the scenes, the MEF **DeploymentCatalog** is used to download XAP files, and Prism keeps the **ModuleCatalog** updated as MEF discovers new modules.

The Boostrapper class overrides the **ConfigureModuleCatalog** method to register additional modules that are referenced directly by the application.

```C#
    // when using Unity
    protected override void ConfigureModuleCatalog()
    {
        // Module A is defined in the code.
        Type moduleAType = typeof(ModuleA.ModuleA);
        this.ModuleCatalog.AddModule(new ModuleInfo(moduleAType.Name, moduleAType.AssemblyQualifiedName));

        // Module C is defined in the code.
        Type moduleCType = typeof(ModuleC.ModuleC);
        this.ModuleCatalog.AddModule(new ModuleInfo(moduleCType.Name, moduleCType.AssemblyQualifiedName));
    } 
```

When using MEF, the **AggregateCatalog** provides module and type discovery. In this case, the **Bootstrapper** overrides the **ConfigureAggregateCatalog** method and registers assemblies with MEF.

```C#
    // when using MEF
    protected override void ConfigureAggregateCatalog()
    {
        base.ConfigureAggregateCatalog();
        // Add this assembly to export ModuleTracker.
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(Bootstrapper).Assembly));

        // Module A is referenced in in the project and directly in code.
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(ModuleA.ModuleA).Assembly));

        // Module C is referenced in in the project and directly in code.
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(ModuleC.ModuleC).Assembly));
    }
```

## Loading Modules

This QuickStart demonstrates both loading modules at startup and on demand, downloading modules in the background while displaying progress, and handling dependencies between modules.

> [!NOTE]
> This QuickStart has additional classes that help to track module initialization state and artificially slow down the transfer of XAP files. These classes are for demonstration purposes only and are not intended for shipping applications.<br />
The Shell user interface contains a **ModuleControl** for each module. The Shell also has the **ModuleTracker** class as its **DataContext**.<br />
The **ModuleTracker** contains a **ModuleTrackingState** for each module. **ModuleControl** data binds to **ModuleTrackingState** and uses a custom style to visually display the downloading and initialized state of the module.<br />
The **XapDownloadHandler** (in the Silverlight.Web project) artificially slows down the transfer of XAP files so that the QuickStart can display progress.

The **Shell** responds to a request from the user interface (UI) to load a module and call the **ModuleManager**.**LoadModule** method.

```C#
    private void ModuleC_RequestModuleLoad(object sender, EventArgs e)
    {
        // The ModuleManager uses the Async Events pattern.
        this.moduleManager.LoadModule(WellKnownModuleNames.ModuleC);
    }
```

The Shell is notified of download progress by subscribing to the **ModuleManager**.**ModuleDownloadProgressChanged** event.

```C#
    this.moduleManager.ModuleDownloadProgressChanged += this.ModuleManager_ModuleDownloadProgressChanged;
```

```C#
    void ModuleManager_ModuleDownloadProgressChanged(object sender, 
         ModuleDownloadProgressChangedEventArgs e)
    {
        this.moduleTracker.RecordModuleLoading(e.ModuleInfo.ModuleName, e.BytesReceived, 
            e.TotalBytesToReceive);
    }
```

The Shell is notified when the module is downloaded and initialized by subscribing to the **ModuleManager.LoadModuleCompleted** event.

```C#
    this.moduleManager.LoadModuleCompleted += this.ModuleManager_LoadModuleCompleted;
```

```C#
    void ModuleManager_LoadModuleCompleted(object sender, LoadModuleCompletedEventArgs e)
    {
        this.moduleTracker.RecordModuleLoaded(e.ModuleInfo.ModuleName);
    }
```

## Key Modularity Classes

The following are some key classes used in the modularity QuickStarts:

-   **ModuleCatalog**. This class is responsible for cataloging the metadata for modules and module groups in the application.
-   **ModuleManager**. This class coordinates the initialization of the modules. It manages the retrieval and the subsequent initialization of the modules.
-   **ModuleInitializer**. This class assists the **ModuleManager** in creating instances of modules.
-   **IModuleTypeLoader**. This is the interface for derived types (for example, the **XapModuleTypeLoader** class) to retrieve modules from the file system or a remote server.
-   **Bootstrapper**/**MefBootstrapper**/**UnityBootstrapper**. This class assists applications in starting an initializing a modular Prism application.

## Acceptance Tests

The Modularity QuickStarts include a separate solution with acceptance tests for both QuickStarts. Acceptance tests describe how an application should perform when you follow a series of steps; you can use the acceptance tests to explore the functional behavior of the applications in a variety of scenarios.

**To run the Modularity QuickStarts acceptance tests**

1.  In Visual Studio, open one of the following solution files:
    -   QuickStarts\\Modularity\\ModularityWithUnity.Tests.AcceptanceTest\\ModularityWithUnity.Tests.AcceptanceTest.sln
    -   QuickStarts\\Modularity\\ModularityWithMEF.Tests.AcceptanceTest\\ModularityWithMEF.Tests.AcceptanceTest.sln
2.  Right-click either the ModularityWithMEF.Tests.AcceptanceTest solution or the ModularityWithUnity.Tests.AcceptanceTest solution, and then click **Set as StartUp Project**.
3.  Press F5.

## Outcome

When you run the acceptance tests, you should see the QuickStarts windows and the tests automatically interact with the user interface. At the end of the test pass, you should see that all tests have passed.

## More Information

To learn more about modularity, see [Modular Application Development](http://msdn.microsoft.com/en-us/library/gg405479(v=pandp.40).aspx) on MSDN or in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580).

To learn about other QuickStarts included with Prism, see the following topics in the [Prism4.pdf](http://compositewpf.codeplex.com/releases/view/55580):

-   Modularity QuickStarts for WPF
-   Basic MVVM QuickStart
-   MVVM QuickStart
-   Commanding QuickStart
-   UI Composition QuickStart
-   State-Based Navigation QuickStart
-   View-Switching Navigation QuickStart
-   Event Aggregation QuickStart
-   [Multi-Targeting QuickStart](/guide/multi-targeting-quickstart(v=pandp.40)) (also available on MSDN)

