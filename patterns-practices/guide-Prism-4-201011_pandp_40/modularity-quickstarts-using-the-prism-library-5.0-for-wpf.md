---
TOCTitle: 'Modularity QuickStarts Using the Prism Library 5.0 for WPF'
Title: 'Modularity QuickStarts Using the Prism Library 5.0 for WPF'
ms:assetid: '5ddf28b3-8d8a-4a02-9f0d-a70a64b9d130'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Ff921068(v=PandP.40)'
---

# Modularity QuickStarts Using the Prism Library 5.0 for WPF

From: [Developer's Guide to Microsoft Prism Library 5.0 for WPF](https://msdn.microsoft.com/en-us/library/gg406140.aspx)

Modulatiry QuickStarts source code:

-   Download [Unity version](http://aka.ms/prism-wpf-qsmodularityunitycode)
-   Download [MEF version](http://aka.ms/prism-wpf-qsmodularitymefcode)

The QuickStarts included in this topic provide code samples that demonstrate how to create a modular WPF application using the Prism library. The samples demonstrate how to code, discover, and initialize modules:

-   **Creating modules**. Modules are classes that implement the **IModule** interface. Declarative attributes can be used to name modules, control initialization, and define dependencies.
-   **Registering modules**. Modules can be registered in the following ways:
    -   **Directly in code**. Modules can be directly registered in the module catalog in the application code. Using this approach, you can use conditional logic to determine which module should be included in your application. Modules added in code are referenced by the application instead of being loaded at run time.
    -   **Using configuration**. Prism can register modules with the module catalog by loading a configuration file. Declaring the modules in configuration allows the modules to be loaded and initialized independent of the application.
    -   **Using directory inspection**. A directory can be specified and inspected to load assemblies in the directory and discover modules.
-   **Registering module dependencies**. Modules can have dependencies on other modules. Prism provides dependencies management, including cyclic dependencies and duplicate module detection.
-   **Initializing modules**. Prism supports the following two initialization modes:
    -   **When available**. Modules can be initialized as soon as they are available. Modules downloaded with the application are initialized during startup. Modules set to download in the background are initialized immediately after downloading completes.
    -   **On-demand**. Modules can be initialized when the application code requests it. Modules downloaded in the background start downloading when the application requests the module, and then they initialize immediately after downloading completes.
-   **Downloading modules in the background**. Although downloading in the background is most useful to Silverlight applications, desktop applications can now take advantage of the same progress and completion events as assemblies are discovered and loaded:
    -   **Displaying progress**. An application can subscribe to a progress-changed event to display byte count and percentage progress as modules are downloaded.
    -   **Action on download complete**. An application can subscribe to a load module–completed event to take additional action after a module loads and initializes.
-   **Leveraging different dependency injection containers**. Traditionally, the QuickStarts have demonstrated using the Unity container, while the core library code remained container-agnostic. With the addition of Managed Extensibility Framework (MEF) to the .NET Framework 4, there are two QuickStarts, each of which uses a different container:
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
<td><p>Directory</p></td>
<td><p>On demand</p></td>
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
<td><p>Directory</p></td>
<td><p>When available</p></td>
<td><p>In background</p></td>
<td><br />
</td>
</tr>
<tr class="odd">
<td><p>E</p></td>
<td><p>Configuration</p></td>
<td><p>On demand</p></td>
<td><p>In background</p></td>
<td><br />
</td>
</tr>
<tr class="even">
<td><p>F</p></td>
<td><p>Configuration</p></td>
<td><p>On demand</p></td>
<td><p>In background</p></td>
<td><p>E</p></td>
</tr>
</tbody>
</table>

Each QuickStart displays each module as a control. The module control indicates whether it has been initialized, displays downloading progress, and on-demand modules can be clicked to request initialization. The control also provides a tooltip that shows its current initialization state and discovery information. At the bottom of each QuickStart page is a text box that displays the log entries from the bootstrapping sequence and module-loading details. The following illustration shows the main page of the Modularity with MEF QuickStart.

![](https://msdn.microsoft.com/en-us/Ff921068.1CB1D9C3CA3AFB26BF4DA2F4E691F0BA(en-us,PandP.40).png "Modularity QuickStart user interface")

Modularity QuickStart user interface

## Building and Running the QuickStarts

This QuickStart requires Microsoft Visual Studio 2012 or later with .NET Framework 4.5.1.

**To build and run the ModularityWithMef QuickStart**

1.  In Visual Studio, open the solution file Quickstarts\\Modularity\\Desktop\\ModularityWithMef\\ModularityWithMef.Desktop.sln.
2.  In the **Build** menu, click **Rebuild Solution**.
3.  Press F5 to run the QuickStart.

**To build and run the ModularityWithUnity QuickStart**

1.  In Visual Studio, open the +solution file Quickstarts\\Modularity\\Desktop\\ModularityWithUnity\\ModularityWithUnity.Desktop.sln.
2.  In the **Build** menu, click **Rebuild Solution**.
3.  Press F5 to run the QuickStart.

>**Note:** Both QuickStarts have post-build events configured on each module project to automatically store the modules' assemblies in a folder after a successful build.<br/>
Modules B and D are copied into a DirectoryModules folder and Modules E and F are copied into the same location as the application executable.<br/>
To see the post-build events configuration, right-click a module project, and then click **Properties**. In the **Properties** dialog box, click the **Build Events** tab.<br/>
The following code shows the post-build event command in the **Post-build event command line** text box.
xcopy &quot;$(TargetDir)*.*&quot; &quot;$(SolutionDir)ConfigurationModularity\bin\$(ConfigurationName)\DirectoryModules\&quot; /Y

## Walkthrough

To explore the scenario, perform the steps to build and run the QuickStart:

1.  The main window shows a set of modules, each of which displays the module's initialization state, as shown in the following illustration. As the application starts, Module D and Module A are discovered and initialized.

    ![](https://msdn.microsoft.com/en-us/Ff921068.1CB1D9C3CA3AFB26BF4DA2F4E691F0BA(en-us,PandP.40).png "Main page of Modularity with MEF QuickStart")

    Main page of Modularity with MEF QuickStart

    Module D is discovered by directory inspection at application startup. Module A is initialized when it is available and depends on Module D. After Module D loads, Module A is initialized. The trace window at the bottom shows messages as the application is initialized.

    >**Note:** If no dependencies are specified, the module load order is non-deterministic.

2.  Hover over the **Module A** control. When the mouse hovers over the **Module A** control, a descriptive tooltip is displayed, as shown in the following illustration.

    ![](https://msdn.microsoft.com/en-us/Ff921068.06BED1C32843460767CB2D2F4123A76E(en-us,PandP.40).png "Module Information tooltip")

    Module Information tooltip

3.  As you hover the pointer over a module, a tooltip displays that shows information about its status, discovery, initialization, download timing, and dependencies.
4.  Click the **Module B** and **Module C** controls. As each module initialization state changes, the visual control is updated. When either the **Module B** control or the **Module C** control is clicked, that module gets loaded, as shown in the following illustration.

    ![](https://msdn.microsoft.com/en-us/Ff921068.E23B95D15C5CDE745200083BD37E4188(en-us,PandP.40).png "Screen shot of module loaded")

    Screen shot of module loaded

    Module B is discovered by directory inspection, and Module C is referenced by the application. Both modules are loaded on demand.

5.  Click the **Module F** control. When the **Module F** control is clicked, Module E and Module F get loaded, as shown in the following illustration.

    ![](https://msdn.microsoft.com/en-us/Ff921068.E5671E79DE7110409735E6E692A99871(en-us,PandP.40).png "Screen shot of Module E getting loaded to load Module F")

    Screen shot of Module E getting loaded to load Module F

    Notice that Module F completes its initialization first, but is not initialized until after Module E initializes because of the dependency.

## Implementation Details

The QuickStarts highlight the key components in modularity. The following sections describe the key artifacts the QuickStarts.

The **Bootstrapper** overrides several methods from either the **MefBootstrapper** or the **UnityBootstrapper** to support the specifics of the application. These sections describe important differences between dependency injection containers.

## Application Startup

The application uses the **QuickStartBootstrapper** to start the application and initialize the main window.

```C#
    protected override void OnStartup(StartupEventArgs e)
    {
        base.OnStartup(e);

        // The bootstrapper will create the Shell instance, so the App.xaml 
        // does not have a StartupUri.
        QuickStartBootstrapper bootstrapper = new QuickStartBootstrapper();
        bootstrapper.Run();
    }
```

The **Bootstrapper** overrides **CreateShell** and **InitializeShell** methods to create and show the main window.

```C#
    protected override DependencyObject CreateShell()
            {
                return ServiceLocator.Current.GetInstance<Shell>();
            }

    protected override void InitializeShell()
    {
        base.InitializeShell();

        Application.Current.MainWindow = (Window)this.Shell;
        Application.Current.MainWindow.Show();
    }
```

## Creating Modules

In this QuickStart, six modules are created by implementing the **IModule** interface. Attributes are added, depending on the dependency injection container chosen (that is, Unity or MEF).

```C#
    // when using Unity
    [Module(ModuleName = WellKnownModuleNames.MyModule)]
    [ModuleDependency(WellKnownModuleNames.DependentModule)]
    public class MyModule: IModule
    {
        ...
    }
```

When using Unity, attributes can be used to name the module and specify dependencies.

```C#
    // when using MEF
    [ModuleExport(typeof(ModuleA), DependsOnModuleNames = new string[] { "ModuleD" })]
    public class ModuleA : IModule
    {
        ...
    }
```

When using MEF, the **ModuleExport** attribute allows MEF to discover the appropriate type deriving from the **IModule** interface; in addition, it provides the ability to specify additional module metadata.

## Registering Modules

In this QuickStart, some modules are directly referenced by the application, discovered by inspecting a directory, or registered by loading a configuration file.

The **QuickStartBootstrapper** overrides **CreateModuleCatalog** and **ConfigureModuleCatalog** methods to register modules.

```C#
    // when using Unity
    protected override IModuleCatalog  CreateModuleCatalog()
    {
        return new AggregateModuleCatalog();
    } 

    // when using Unity
    protected override void ConfigureModuleCatalog()
    {
        // Module A is defined in the code.
        Type moduleAType = typeof(ModuleA);
        ModuleCatalog.AddModule(new ModuleInfo(moduleAType.Name, 
    moduleAType.AssemblyQualifiedName));

        // Module C is defined in the code.
    Type moduleCType = typeof(ModuleC);    ModuleCatalog.AddModule(new ModuleInfo()         {            ModuleName = moduleCType.Name,            ModuleType = moduleCType.AssemblyQualifiedName,            InitializationMode = InitializationMode.OnDemand         });

        // Module B and Module D are copied to a directory as part of a post-build step.
        // These modules are not referenced in the project and are discovered by
        // inspecting a directory.
        // Both projects have a post-build step to copy themselves into that directory.
        DirectoryModuleCatalog directoryCatalog = new DirectoryModuleCatalog() { ModulePath = @".\DirectoryModules" };
        ((AggregateModuleCatalog)ModuleCatalog).AddCatalog(directoryCatalog);
        // Module E and Module F are defined in configuration.
        ConfigurationModuleCatalog configurationCatalog = new ConfigurationModuleCatalog();
         ((AggregateModuleCatalog)ModuleCatalog).AddCatalog(configurationCatalog);

     }
```

>**Note:** To demonstrate multiple ways of using the **ModuleCatalog**, the QuickStart using Unity implements an **AggregateModuleCatalog** that derives from **IModuleCatalog**. This class is not intended to be used in a shipping application.

When using MEF, the **AggregateCatalog** provides module and type discovery. In this case, the **QuickStartBootstrapper** overrides the **ConfigureAggregateCatalog** template method and registers assemblies with MEF. The **ModuleCatalog** is still used for registering modules by loading a configuration file.

```C#
    // when using MEF
    protected override IModuleCatalog CreateModuleCatalog()
    {
        // When using MEF, the existing Prism ModuleCatalog is still the place to 
        // configure modules via configuration files.
        return new ConfigurationModuleCatalog();
    }
```

```C#
    // when using MEF
    protected override void ConfigureAggregateCatalog()
    {
        base.ConfigureAggregateCatalog();
                
        // Add this assembly to export ModuleTracker.
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(QuickStartBootstrapper).Assembly));
        // Module A is referenced in in the project and directly in code.
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(ModuleA).Assembly));
        this.AggregateCatalog.Catalogs.Add(new AssemblyCatalog(typeof(ModuleC).Assembly));
        // Module B and Module D are copied to a directory as part of a post-build step.
        // These modules are not referenced in the project and are discovered by
        // inspecting a directory.
        // Both projects have a post-build step to copy themselves into that directory.
        DirectoryCatalog catalog = new DirectoryCatalog("DirectoryModules"); 
        this.AggregateCatalog.Catalogs.Add(catalog);
    }
```     

## Loading Modules

This QuickStart demonstrates both loading modules at startup and on demand, displaying progress, and handling dependencies between modules.

>**Note:** This QuickStart has additional classes that help to track module initialization state. These classes are for demonstration purposes only and are not intended for shipping applications.<br/>
The Shell user interface contains a **ModuleControl** for each module. The Shell also has the **ModuleTracker** class as its **DataContext**.<br/>
The **ModuleTracker** contains a **ModuleTrackingState** for each module. **ModuleControl** data binds to **ModuleTrackingState** and uses a custom style to visually display the downloading and initialized state of the module.

The Shell responds to a request from the user interface (UI) to load a module and call the **ModuleManager**.**LoadModule** method.

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
-   **Bootstrapper**/**MefBootstrapper**/**UnityBootstrapper**. This class assists applications in starting and initializing a modular Prism application.

## Acceptance Tests

The Modularity QuickStarts include a separate solution with acceptance tests for both Unity and MEF QuickStarts. Acceptance tests describe how an application should perform when you follow a series of steps; you can use the acceptance tests to explore the functional behavior of the applications in a variety of scenarios.

**To run the Modularity QuickStarts acceptance tests**

1.  In Visual Studio, open one of the following solution files:
    -   QuickStarts\\Modularity\\ModularityWithUnity.Tests.AcceptanceTest\\ModularityWithUnity.Tests.AcceptanceTest.sln
    -   QuickStarts\\Modularity\\ModularityWithMEF.Tests.AcceptanceTest\\ModularityWithMEF.Tests.AcceptanceTest.sln
2.  Build the solution.
3.  Open **Test Explorer**.
4.  After building the solution, Visual Studio finds the tests. Click the **Run All** button to run the acceptance tests.

## Outcome

When you run the acceptance tests, you should see the QuickStarts windows and the tests automatically interact with the user interface. At the end of the test pass, you should see that all tests have passed.

## More Information

To learn more about modularity, see [Modular Application Development](https://msdn.microsoft.com/en-us/library/gg405479(v=pandp.40)).

To learn about other code samples included with Prism, see the following topics:

-   [Stock Trader Reference Implementation](https://msdn.microsoft.com/en-us/library/ff921074(v=pandp.40))
-   [Interactivity QuickStart](https://msdn.microsoft.com/en-us/library/ff921081(v=pandp.40))
-   [MVVM QuickStart](https://msdn.microsoft.com/en-us/library/gg430857(v=pandp.40))
-   [Commanding QuickStart](https://msdn.microsoft.com/en-us/library/ff921082(v=pandp.40))
-   [UI Composition QuickStart](https://msdn.microsoft.com/en-us/library/ff921174(v=pandp.40))
-   [State-Based Navigation QuickStart](https://msdn.microsoft.com/en-us/library/gg405495(v=pandp.40))
-   [View-Switching Navigation QuickStart](https://msdn.microsoft.com/en-us/library/gg430881(v=pandp.40))
-   [Event Aggregation QuickStart](https://msdn.microsoft.com/en-us/library/ff921173(v=pandp.40))

Next Topic | Previous Topic | [Home](http://msdn.microsoft.com/en-us/library/gg406140) | [Community](https://compositewpf.codeplex.com/)
