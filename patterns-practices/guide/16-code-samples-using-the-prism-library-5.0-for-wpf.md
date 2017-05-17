---
TOCTitle: '16: Code Samples Using the Prism Library 5.0 for WPF'
Title: '16: Code Samples Using the Prism Library 5.0 for WPF'
ms:assetid: '93cb57bd-7652-4666-8d1a-2f0e71c8efe6'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430879(v=PandP.40)'
---

# 16: Code Samples Using the Prism Library 5.0 for WPF

From: [Developer's Guide to Microsoft Prism Library 5.0 for WPF](https://msdn.microsoft.com/en-us/library/gg406140.aspx)

The code samples for the Prism Library for WPF are focused applications that illustrate specific Prism-related concepts. The QuickStarts and Reference Implementation are an ideal starting point if you want to gain an understanding of a key concept such as Modularity, MVVM, Commands, UI Composition, Navigation, Event Aggregations, User Interactivity, and Composite Application. The Stock Trader Reference Implementation demonstrates proven practices for implementing composite applications. The samples include both source code and documentation.

In order to build and run the samples select the appropriate shortcut file and press F5 to build and run.

## Installing Prism

This section describes how to install Prism. It involves the following three steps:

1.  Install system requirements.
2.  Extract the Prism source code and documentation.
3.  Compile and run QuickStarts, Reference Implementation or Prism Library source code.

## Step 1: Install System Requirements

Prism was designed to run on the Microsoft Windows 8 desktop, Microsoft Windows 7, Windows Vista, or Windows Server 2008 operating system. WPF applications built using this guidance require the .NET Framework 4.5.

Before you can use the Prism Library, the following must be installed:

-   Microsoft .NET Framework 4.5 (installed with Visual Studio 2012) or Microsoft .NET Framework 4.51.
-   Microsoft Visual Studio 2012 Professional, Premium, or Ultimate editions or Microsoft Visual Studio 2013 Professional, Premium, or Ultimate editions.

> [!NOTE]
> Visual Studio 2013 Express Edition can be used to develop Prism applications using the Prism Library.

Optionally, you should consider also installing the following:

-   [Microsoft Blend for Visual Studio 2013](http://www.microsoft.com/expression/products/blend_overview.aspx). A professional design tool for creating compelling user experiences and applications for WPF.

## Step 2: Extract the Prism Source Code, and Documentation

To install the Prism assets, right-click the downloaded file, and then click **Run as administrator**. This will extract the source code and documentation into the folder of your choice. You may also need to right-click the file and unblock before you can extract the contents.

## Step 3: Compile and run QuickStarts, Reference Implementation or Prism Library source code.

In order to build and run the code sample, select the appropriate shortcut file and press F5 to build and run.

<table>
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Code sample download from Code Gallery</p></th>
<th><p>Category</p></th>
<th><p>Summary</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921074(v=pandp.40)">Stock Trader Reference Implementation</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-ricode">Download Stock Trader RI code</a></p></td>
<td><p>Prism</p></td>
<td><p>The Stock Trader RI application is a reference implementation that illustrates the baseline architecture. Within the application, you will see solutions for common, and recurrent, challenges that developers face when creating composite WPF applications.</p>
<p>The Stock Trader RI illustrates a fictitious, but realistic financial investments scenario. Contoso Financial Investments (CFI) is a fictional financial organization that is modeled after real financial organizations. CFI is building a new composite application to be used by their stock traders.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921141(v=pandp.40)">Hello World QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qshelloworldcode">Download Hello World QuickStart code</a></p>
<br />
</td>
<td><p>Get Started</p></td>
<td><p>The Hello World QuickStarts are the ending solution for the <a href="https://msdn.microsoft.com/en-us/library/ff921141(v=pandp.40)">Getting Started Using the Prism Library Hands-on Lab</a>. In this lab, you will learn the basic concepts of Prism and apply them to create a Prism Library solution that you can use as the starting point for building a composite WPF.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921068(v=pandp.40)">Modularity QuickStarts</a></p></td>
<td><ul>
<li><a href="http://aka.ms/prism-wpf-qsmodularityunitycode">Download Modularity QuickStart code for Unity</a></li>
<li><a href="http://aka.ms/prism-wpf-qsmodularitymefcode">Download Modularity QuickStart code for MEF</a></li>
</ul></td>
<td><p>Modularity</p></td>
<td><p>The Modularity QuickStarts demonstrate how to code, discover, and initialize modules using Prism. These QuickStarts represent an application composed of several modules that are discovered and loaded in the different ways supported by the Prism Library using MEF and Unity as the composition containers.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921081(v=pandp.40)">Interactivity QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qsinteractivitycode">Download Interactivity QuickStart code</a></p>
<br />
</td>
<td><p>Interactivity</p></td>
<td><p>This QuickStart demonstrates how to create a view and view model that work together when the view model needs to interact with the user or user gesture needs to raise an event that invokes a command. In each of these scenarios the view model should not need to know about the view. The first scenario is handled by using <strong>InteractionRequests</strong> and <strong>InteractionRequestTriggers</strong>. The second scenario is handled by <strong>InvokeCommandAction</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/en-us/library/gg430857(v=pandp.40)">MVVM QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qsmvvmcode">Download MVVM QuickStart code</a></p></td>
<td><p>MVVM</p></td>
<td><p>The MVVM QuickStart demonstrates how to build a very simple application that implements the MVVM pattern.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921082(v=pandp.40)">Commanding QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qscommandingcode">Download Command QuickStart code</a></p></td>
<td><p>Commanding</p></td>
<td><p>The Commanding QuickStart demonstrates how to build a WPF UI that uses commands provided by the Prism Library to handle UI actions in a decoupled way.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921174(v=pandp.40)">UI Composition QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qsuicompositioncode">Download UI Composition QuickStart code</a></p></td>
<td><p>UI Composition</p></td>
<td><p>This QuickStart demonstrates how to build WPF UIs composed of different views that are dynamically loaded into regions and that interact with each other in a decoupled way. It illustrates how to use both the view discovery and view injection approaches for UI composition.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/en-us/library/gg405495(v=pandp.40)">State-Based Navigation QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qsstatebasednavcode">State-Based Navigation QuickStart</a></p></td>
<td><p>Navigation</p></td>
<td><p>This QuickStart demonstrates an approach to define the navigation of a simple application. The approach used in this QuickStart uses the WPF Visual State Manager (VSM) to define the different states that the application has and defines animations for both the states and the transitions between states.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://msdn.microsoft.com/en-us/library/gg430881(v=pandp.40)">View-Switching Navigation QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qsviewswitchnavcode">Download View-Switching Navigation QuickStart code</a></p>
<br />
</td>
<td><p>Navigation</p></td>
<td><p>This QuickStart demonstrates how to use the Prism Region Navigation API. The QuickStart shows multiple navigation scenarios, including navigating to a view in a region, navigating to a view in a region contained in another view (nested navigation), navigation journal support, just-in-time view creation, passing contextual information when navigating to a view, views and view models participating in navigation, and using navigation as part of an application built through modularity and UI composition.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://msdn.microsoft.com/en-us/library/ff921173(v=pandp.40)">Event Aggregation QuickStart</a></p></td>
<td><p><a href="http://aka.ms/prism-wpf-qseacode">Download Event Aggregation QuickStart code</a></p></td>
<td><p>Event Aggregation</p></td>
<td><p>This QuickStart demonstrates how to build a WPF application that uses the Event Aggregator service. This service enables you to establish loosely coupled communications between components in your application.</p></td>
</tr>
</tbody>
</table>

