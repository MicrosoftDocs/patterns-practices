---
TOCTitle: 'Download and Setup Prism Library 5.0 for WPF'
Title: 'Download and Setup Prism Library 5.0 for WPF'
ms:assetid: 'b34b3dc3-b4a5-47d3-ab19-2168de337ef3'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405471(v=PandP.40)'
---

# Download and Setup Prism Library 5.0 for WPF

From: [Developer's Guide to Microsoft Prism Library 5.0 for WPF](https://msdn.microsoft.com/en-us/library/gg406140.aspx)

Learn what’s included in Prism 5.0 including the documentation, WPF code samples, and libraries. Additionally find out where to get the library and sample source code and the library NuGet packages.

For a list of the new features, assets, and API changes, see [What's New in Prism 5.0](https://msdn.microsoft.com/en-us/library/gg430871(v=pandp.40)).

## Documentation

Prism includes the following documentation:

-   [Developer's Guide to Microsoft Prism 5.0 on MSDN](http://aka.ms/prism-wpf-doc).
-   [Prism Reference Documentation on MSDN](http://aka.ms/prism-wpf-prism50refdoc).
-   [Developer's Guide to Microsoft Prism 5.0 in .pdf format](http://aka.ms/prism-wpf-pdf).
-   [Prism Reference Documentation in chm format](http://aka.ms/prism-wpf-prism50refdocchm).

## NuGet Packages

-   [Prism](http://aka.ms/prism-wpf-prism50nuget): Downloads NuGet dependency packages—Prism.Composition, Prism.Interactivity, Prism.Mvvm, and Prism.PubSubEvents NuGet Packages.
-   [Prism.Composition](http://aka.ms/prism-wpf-prism50compositionnuget): Modularity, UI Composition, Bootstrapping, Interactivity, IActiveAware, Navigation, and deprecated NotificationObject and PropertySupport.
-   [Prism.Interactivity](http://aka.ms/prism-wpf-prism50interactivitynuget): Interactivity.
-   [Prism.Mvvm](http://aka.ms/prism-wpf-prism50mvvmnuget): The Portable Class Library for MVVM and the associated platform specific code to support MVVM. Includes Commanding, BindableBase, ErrorsContainer, IView, and ViewModelLocationProvider.
-   [Prism.PubSubEvents](http://aka.ms/prism-wpf-prism50pubsubeventsnuget): The Portable Class Library for PubSubEvents.
-   [Prism.UnityExtensions](http://aka.ms/prism-wpf-prism50unityextensionsnuget): Use these extensions to Prism to build Prism applications based on Unity.
-   [Prism.MefExtensions](http://aka.ms/prism-wpf-prism50mefextensionsnuget): Use these extensions to Prism to build Prism applications based on Managed Extensibility Framework (MEF).

The following table shows common Prism namespaces and in which assemblies and NuGet packages they can be found.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Namespace</p></th>
<th><p>Assembly</p></th>
<th><p>NuGet Package</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft.Practices.Prism.Logging</p>
<p>Microsoft.Practices.Prism.Modularity Microsoft.Practices.Prism.Regions</p></td>
<td><p>Microsoft.Practices.Prism.Composition</p></td>
<td><p>Prism.Composition</p></td>
</tr>
<tr class="even">
<td><p>Microsoft.Practices.Prism.Interactivity</p></td>
<td><p>Microsoft.Practices.Prism.Interactivity</p></td>
<td><p>Prism.Interactivity</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft.Practices.Prism.Commands</p>
<p>Microsoft.Practices.Prism.Mvvm</p>
<p>Microsoft.Practices.Prism.ViewModel</p></td>
<td><p>Microsoft.Practices.Prism.Mvvm</p></td>
<td><p>Prism.Mvvm</p></td>
</tr>
<tr class="even">
<td><p>Microsoft.Practices.Prism.PubSubEvents</p></td>
<td><p>Microsoft.Practices.Prism.PubSubEvents</p></td>
<td><p>Prism.PubSubEvents</p></td>
</tr>
</tbody>
</table>


## Download and Setup the Prism Source Code

This section describes how to install Prism. It involves the following three steps:

1.  Install system requirements.
2.  Download and extract the Prism source code and documentation.
3.  Compile and run the QuickStarts, Reference Implementation, or Prism Library source code.

## Step 1: Install System Requirements

Prism was designed to run on the Microsoft Windows 8 desktop, Microsoft Windows 7, Windows Vista, or Windows Server 2008 operating system. WPF applications built using this guidance require the .NET Framework 4.5.

Before you can use the Prism Library, the following must be installed:

-   Microsoft .NET Framework 4.5 (installed with Visual Studio 2012) or Microsoft .NET Framework 4.51.
-   Microsoft Visual Studio 2012 or 2013 Professional, Premium, or Ultimate editions.

> [!NOTE]
> Visual Studio 2013 Express Edition can be used to develop Prism applications using the Prism Library.

Optionally, you should consider also installing the following:

-   [Microsoft Blend for Visual Studio 2013](http://www.microsoft.com/expression/products/blend_overview.aspx). A professional design tool for creating compelling user experiences and applications for WPF.

## Step 2: Download and Extract the Prism Source Code and Documentation

You can download the source code for the Prism library, the reference implementation and the QuickStarts from the following link:

-   [**Prism 5.0**](http://aka.ms/prism-wpf-code)

To install the Prism assets, right-click the exe file or zip file, and then click **Run as administrator**. This will extract the source code into the folder of your choice.

> [!NOTE]
> The Stock Trader Reference Implementation and the QuickStarts can also be downloaded separately. The table below provides links to the source code for each.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sample</p></th>
<th><p>Category</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="http://aka.ms/prism-wpf-ricode">Stock Trader Reference Implementation</a></p></td>
<td><p>Prism</p></td>
<td><p>The Stock Trader RI application is a reference implementation that illustrates the baseline architecture. Within the application, you will see solutions for common, and recurrent, challenges that developers face when creating composite WPF applications.</p>
<p>The Stock Trader RI illustrates a fictitious, but realistic financial investments scenario. Contoso Financial Investments (CFI) is a fictional financial organization that is modeled after real financial organizations. CFI is building a new composite application to be used by their stock traders.</p></td>
</tr>
<tr class="even">
<td><p><a href="http://aka.ms/prism-wpf-qshelloworldcode">Hello World Hands-on Lab</a></p></td>
<td><p>Get Started</p></td>
<td><p>The Hello World Hands-on Lab demonstrates the end solution for the hands-on lab &quot;<a href="https://msdn.microsoft.com/en-us/library/ff921141(v=pandp.40)">Getting Started Using the Prism Library 5.0 for WPF Hands-on Lab.</a>&quot; In this lab, you will learn the basic concepts of Prism and apply them to create a Prism Library solution that you can use as the starting point for building a composite WPF.</p></td>
</tr>
<tr class="odd">
<td><ul>
<li><a href="http://aka.ms/prism-wpf-qsmodularityunitycode">Modularity QuickStarts for Unity</a></li>
<li><a href="http://aka.ms/prism-wpf-qsmodularitymefcode">Modularity QuickStarts for MEF</a></li>
</ul></td>
<td><p>Modularity</p></td>
<td><p>The Modularity QuickStarts demonstrate how to code, discover, and initialize modules using Prism. These QuickStarts represent an application composed of several modules that are discovered and loaded in the different ways supported by the Prism Library using MEF and Unity as the composition containers.</p></td>
</tr>
<tr class="even">
<td><p><a href="http://aka.ms/prism-wpf-qsmvvmcode">MVVM QuickStart</a></p></td>
<td><p>MVVM</p></td>
<td><p>The MVVM QuickStart demonstrates how to build an application that implements the MVVM presentation pattern, showing some of the more common challenges that developers can face, such as wiring a view and view model using the ViewModelLocator, validation, UI interactions, and data templates.</p></td>
</tr>
<tr class="odd">
<td><p><a href="http://aka.ms/prism-wpf-qscommandingcode">Commanding QuickStart</a></p></td>
<td><p>Commanding</p></td>
<td><p>The Commanding QuickStart demonstrates how to build a WPF UI that uses commands provided by the Prism Library to handle UI actions in a decoupled way.</p></td>
</tr>
<tr class="even">
<td><p><a href="http://aka.ms/prism-wpf-qsuicompositioncode">UI Composition QuickStart</a></p></td>
<td><p>UI Composition</p></td>
<td><p>This QuickStart demonstrates how to build WPF UIs composed of different views that are dynamically loaded into regions and that interact with each other in a decoupled way. It illustrates how to use both the view discovery and view injection approaches for UI composition.</p></td>
</tr>
<tr class="odd">
<td><p><a href="http://aka.ms/prism-wpf-qsstatebasednavcode">State-Based Navigation QuickStart</a></p></td>
<td><p>Navigation</p></td>
<td><p>This QuickStart demonstrates an approach to define the navigation of a simple application. The approach used in this QuickStart uses the WPF Visual State Manager (VSM) to define the different states that the application has and defines animations for both the states and the transitions between states.</p></td>
</tr>
<tr class="even">
<td><p><a href="http://aka.ms/prism-wpf-qsviewswitchnavcode">View-Switching Navigation QuickStart</a></p></td>
<td><p>Navigation</p></td>
<td><p>This QuickStart demonstrates how to use the Prism Region Navigation API. The QuickStart shows multiple navigation scenarios, including navigating to a view in a region, navigating to a view in a region contained in another view (nested navigation), navigation journal support, just-in-time view creation, passing contextual information when navigating to a view, views and view models participating in navigation, and using navigation as part of an application built through modularity and UI composition.</p></td>
</tr>
<tr class="odd">
<td><p><a href="http://aka.ms/prism-wpf-qseacode">Event Aggregation QuickStart</a></p></td>
<td><p>Event Aggregation</p></td>
<td><p>This QuickStart demonstrates how to build a WPF application that uses the Event Aggregator service. This service enables you to establish loosely coupled communications between components in your application.</p></td>
</tr>
<tr class="even">
<td><p><a href="http://aka.ms/prism-wpf-qsinteractivitycode">Interactivity QuickStart</a></p></td>
<td><p>Interactivity</p></td>
<td><p>This QuickStart demonstrates how to create a view and view model that work together when the view model needs to interact with the user or user gesture needs to raise an event that invokes a command. In each of these scenarios the view model should not need to know about the view. The first scenario is handled by using <strong>InteractionRequests</strong> and <strong>InteractionRequestTriggers</strong>. The second scenario is handled by <strong>InvokeCommandAction</strong>.</p></td>
</tr>
</tbody>
</table>

## Step 3: Compile and Run QuickStarts, Reference Implementation, or Prism Library Source Code


In order to build and run the reference implementation and the QuickStarts, select the appropriate shortcut file and press F5 to build and run.

The reference implementation and QuickStarts use NuGet references to the Prism library assemblies so you can compile and run each solution directly.


## Adding Prism Library Source Projects to Solutions


As part of shipping the Prism Library as NuGet packages, the Prism Library projects were removed from the solutions of all QuickStarts and reference implementation projects. If you are a developer accustomed to stepping through the Prism Library code as you build your application, there are a couple of options:

-   **Add the Prism Library Projects back in**. To do this, right-click the solution, point to **Add**, and then click **Existing project**. Select the Prism Library projects. Then, to prevent inadvertently building these, click **Configuration Manager** on the **Build** menu, and then clear the **Build** check box for all Prism Library projects in both the debug and release configurations.
-   **Set a breakpoint and step in**. Set a break point in your application's bootstrapper, and then step in to a method within the base class (F11 is the typical C# keyboard shortcut for this). You may be asked to locate the Prism Library source code, but often, the full program database (PDB) file is available and the file will simply open. You may set breakpoints in any Prism Library project by opening the file and setting the breakpoint.

## Related Downloads


-   [ManifestManagerUtility for ClickOnce](http://compositewpf.codeplex.com/releases/view/14771)
-   [Getting Started Using the Prism Library Hands-on Lab](https://msdn.microsoft.com/en-us/library/gg405497(v=pandp.40))
-   [MVVM Training](http://visualstudiogallery.msdn.microsoft.com/3ab5f02f-0c54-453c-b437-8e8d57eb9942)

Next Topic | Previous Topic | [Community](https://compositewpf.codeplex.com/)
