---
TOCTitle: 'Prism 4.1 - Developer''s Guide to Microsoft Prism Library for WPF and Silverlight'
Title: 'Prism 4.1 - Developer''s Guide to Microsoft Prism Library for WPF and Silverlight'
ms:assetid: 'd4fd190b-4283-4324-8915-0f66e2010a19'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430869(v=PandP.40)'
---

# Prism 4.1 - Developer's Guide to Microsoft Prism Library for WPF and Silverlight

From: [Developer's Guide to Microsoft Prism Library 5.0 for WPF](https://msdn.microsoft.com/en-us/library/gg406140.aspx)

[patterns & practices Developer Center](http://www.microsoft.com/practices)

2012

## Summary

Prism provides guidance designed to help you more easily design and build rich, flexible, and easily maintained Windows Presentation Foundation (WPF) desktop applications, Silverlight Rich Internet Applications (RIAs), and Windows Phone 7 applications. Using design patterns that embody important architectural design principles, such as separation of concerns and loose coupling, Prism helps you to design and build applications using loosely coupled components that can evolve independently but which can be easily and seamlessly integrated into the overall application. These types of applications are known as composite applications.

## Intended Audience

Prism is intended for software developers building WPF or Silverlight applications that typically feature multiple screens, rich user interaction and data visualization, and that embody significant presentation and business logic. These applications typically interact with a number of back-end systems and services and, using a layered architecture, may be physically deployed across multiple tiers. It is expected that the application will evolve significantly over its lifetime in response to new requirements and business opportunities. In short, these applications are "built to last" and "built for change." If your application does not need to last or need to change, then you may not benefit from using Prism.

**Note:** Even single-person projects can realize the benefits by creating more testable and maintainable applications that can evolve over time using the modular approach.

## Architectural Goals

The guidance is designed to help architects and developers achieve the following objectives:

-   Create an application from modules that can be built, assembled and, optionally, deployed by independent teams using WPF or Silverlight.
-   Minimize cross-team dependencies and allow teams to specialize in different areas, such as user interface (UI) design, business logic implementation, and infrastructure code development.
-   Use an architecture that promotes reusability across independent teams.
-   Increase the quality of applications by abstracting common services that are available to all the teams.
-   Incrementally integrate new capabilities.

## System Requirements

This guidance was designed to run on the Microsoft Windows 7, Windows Vista, or Windows Server 2008 operating systems. This version has been smoke tested on Windows XP Professional and Windows Server 2003, but it has not been exhaustively tested. WPF applications built using this guidance require the .NET Framework 4.0, and Silverlight applications require Silverlight 5.

Before you can use the Prism Library, the following must be installed:

-   Microsoft Visual Studio 2010 Professional, Premium, or Ultimate edition
-   Microsoft .NET Framework 4.0 (installed with Visual Studio 2010)
-   [Silverlight Tools for Visual Studio 2010](http://go.microsoft.com/fwlink/?linkid=177428) (required for Silverlight development; includes the developer Silverlight runtime)
-   [Microsoft Silverlight 5 Tools for Visual Studio 2010](http://go.microsoft.com/fwlink/?linkid=229318) (required for Silverlight development; includes the developer Silverlight runtime)
-   Optional tools:
    -   [Expression Blend 4](http://www.microsoft.com/expression/products/blend_overview.aspx)
    -   [Windows Phone Developer Tools SDK](http://go.microsoft.com/fwlink/?linkid=185968) (for development with the Windows Phone 7)

>**Note:** If you want to download the Prism 4.0 – November 2010 release to use with .NET Framework 4.0, Visual Studio 2010, Silverlight 4.0, and Windows Phone 7, go [here for the Prism 4.0 Download](http://www.microsoft.com/en-us/download/details.aspx?displaylang=en&id=4922). The documentation did not change between Prism 4.0 – November 2010 and Prism 4.1 – February 2012.

>**Note:** Although the Silverlight Tools for Visual Studio 2010 are not required, it is recommended that all WPF and Silverlight developers download and use the latest version of the Silverlight Tools for Visual Studio 2010. The WPF and Silverlight Designer for Visual Studio is updated together with the Silverlight developer runtime and SDK. These updates come in the form of new features and bug fixes.

If you are authoring WPF and Silverlight projects that share code, you may want to read [Sharing Code Between WPF and Silverlight,](http://msdn.microsoft.com/library/ff921109(pandp.40).aspx) and install the [Project Linker 2.2](http://visualstudiogallery.msdn.microsoft.com/en-us/5e730577-d11c-4f2e-8e2b-cbb87f76c044) tool.

## Resources

The following table contains Prism download links to help you get started with Prism.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Downloads</p></td>
<td><p><a href="http://www.microsoft.com/download/en/details.aspx?displaylang=en&amp;id=28950">Prism 4.1</a> (includes Prism 4.1 source code, binaries, documentation in CHM format, Reference Implementations, QuickStarts, and Hands-on Labs in C#) for the .NET Framework 4.0 and Silverlight 5.</p>
<p><a href="http://www.microsoft.com/download/en/details.aspx?displaylang=en&amp;id=4922">Prism 4.0</a> (includes Prism 4.0 source code, binaries, documentation in .chm format, Reference Implementations, QuickStarts, and Hands-on Labs in C#) for the .NET Framework 4.0 and Silverlight 4.</p>
<p>Developer's Guide to Microsoft Prism 4 on <a href="http://msdn.microsoft.com/en-us/library/gg430865(pandp.40).aspx">MSDN</a>.</p>
<p>Developer's Guide to Microsoft Prism 4 in <a href="http://oreilly.com/catalog/0790145315496/">printed book and eBook formats</a>.</p>
<p><a href="https://msdn.microsoft.com/en-us/library/gg405483(v=pandp.40)">Prism NuGet Packages</a></p>
<p><a href="http://compositewpf.codeplex.com/releases/view/55580">Developer's Guide to Microsoft Prism 4 in .pdf format</a></p>
<p><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bd727f0f-a52d-4503-b006-a91c375b9241">Visual Basic Prism 4 Reference Implementations, QuickStarts, and Hands-on Labs</a></p></td>
</tr>
<tr class="even">
<td><p>Getting Started</p></td>
<td><p><a href="https://msdn.microsoft.com/en-us/library/gg405483(v=pandp.40)">Prism 4.1 ReadMe</a> (includes installation instructions).</p>
<p><a href="http://compositewpf.codeplex.com/releases/view/55580">Introduction</a></p>
<p><a href="http://compositewpf.codeplex.com/releases/view/55580">What's New in Prism 4</a></p></td>
</tr>
<tr class="odd">
<td><p>Book</p></td>
<td><p><a href="http://shop.oreilly.com/product/0790145315496.do"><img src="https://msdn.microsoft.com/en-us/Gg430869.Prism4Cover(en-us,PandP.40).png" alt="book"/></a></p>
<p><a href="http://shop.oreilly.com/product/0790145315496.do">Buy book</a></p></td>
</tr>
<tr class="even">
<td><p>Upgrading</p></td>
<td><p><a href="https://msdn.microsoft.com/en-us/library/gg430859(v=pandp.40)">Updgrading from Prism 2.x</a></p>
<p><a href="http://compositewpf.codeplex.com/releases/view/55580">Upgrading from the Composite Application Guidance for WPF</a></p>
<p><a href="http://compositewpf.codeplex.com/releases/view/55580">Upgrading from the Composite UI Application Block</a></p></td>
</tr>
<tr class="odd">
<td><p>Related Download</p></td>
<td><p><a href="http://compositewpf.codeplex.com/releases/view/14771">ManifestManagerUtility for ClickOnce</a>.</p>
<p><a href="https://msdn.microsoft.com/en-us/library/gg405497(v=pandp.40)">Publishing and Updating Applications Using the Prism Library Hands-on Lab</a></p>
<p><a href="http://visualstudiogallery.msdn.microsoft.com/3ab5f02f-0c54-453c-b437-8e8d57eb9942">MVVM Training</a></p></td>
</tr>
<tr class="even">
<td><p>Community Feedback and Support</p></td>
<td><p><a href="http://www.codeplex.com/compositewpf">Prism CodePlex Community Site</a></p></td>
</tr>
<tr class="odd">
<td><p>License</p></td>
<td><p><a href="http://msdn.microsoft.com/en-us/library/gg405489(pandp.40).aspx">End User Licensing Agreement (EULA)</a></p></td>
</tr>
</tbody>
</table>

## Guidance Assets

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Documentation</p></td>
<td><p>The documentation for Prism 4 has been completely rewritten and includes the architectural overview, design, and technical concepts for composite applications, applied patterns, two chapters covering Model-View-ViewModel (MVVM), application navigation, Stock Trader Reference Implementation (Stock Trader RI) and MVVM Reference Implementation (MVVM RI) overview, QuickStart overviews, and deployment topics. Much of this guidance is applicable even if you are not using the Prism Library, but you want to know best practices for creating composite applications.</p></td>
</tr>
<tr class="even">
<td><p>Prism Library</p></td>
<td><p>The Prism Library ships as Microsoft signed binaries and source code.</p>
<p>Developers can use the Prism Library to develop WPF or Silverlight applications that are composed of independent and collaborating modules. The library includes extensions to support the integration of the Unity Application Block (Unity) and Managed Extensibility Framework (MEF).</p></td>
</tr>
<tr class="odd">
<td><p>Stock Trader Reference Implementation (Stock Trader RI)</p></td>
<td><p>This application illustrates the baseline Prism architecture. Within the application, you will see solutions for common, and recurrent, challenges that developers face when creating composite applications. The reference implementation is not a real-world application; however, it is based on real-world challenges customers are facing. When you look at this application, do not look at it as a reference point for building a stock trader application; instead, look at is as a reference for building a composite application.</p></td>
</tr>
<tr class="even">
<td><p>MVVM Reference Implementation</p>
<p>(MVVM RI)</p></td>
<td><p>This MVVM RI demonstrates how to build an application that implements the MVVM pattern and shows how to address some advanced challenges that you might face when using this pattern.</p></td>
</tr>
<tr class="odd">
<td><p>QuickStarts</p></td>
<td><p>These include the source code for several small, focused applications that illustrate user interface (UI) composition, modularity, commanding, event aggregation, and multi-targeting applications between WPF and Silverlight. The Getting Started Hands-On Labs provide step-by-step instructions for creating your first application using the Composite Application Library in WPF or Silverlight.</p></td>
</tr>
</tbody>
</table>

## Feedback and Support

To provide feedback about this deliverable, or to get help with any problems, visit the [online Community](http://www.codeplex.com/compositewpf) site at CodePlex.

Prism is designed to be reused, customized, and extended. It is not a Microsoft product. Code-based guidance is shipped "as is" and without warranties. Customers can obtain support through Microsoft Support Services for a fee, but the code is considered user-written.

## Future Plans

The next release of Prism is planned for the summer or fall of 2012. To provide feedback, please create and vote on work items in the CodePlex [issue tracker](http://www.codeplex.com/compositewpf/workitem/list.aspx).

## Related Titles

-   [Prism for Windows for the Windows Runtime](http://msdn.microsoft.com/en-us/library/windows/apps/xx130643.aspx)
-   [Prism Library 5.0 for WPF](http://aka.ms/prism-wpf-doc)
-   [Unity Application Block](http://msdn.microsoft.com/en-us/library/dd203101.aspx)
-   [Enterprise Library](http://msdn.microsoft.com/en-us/library/cc467894.aspx)
-   [Managed Extensibility Framework Overview](http://msdn.microsoft.com/en-us/library/dd460648.aspx)

## Prism Team Blogs

Stay informed and up to date about Prism and patterns & practices.

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Blogs and Home Pages</p></th>
<th><p>Twitter</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Blaine Wastell</p></td>
<td><p><a href="http://blogs.msdn.com/b/blaine/" class="uri">http://blogs.msdn.com/b/blaine/</a></p></td>
<td><p><a href="https://twitter.com/blainewastell">@blainewastell</a></p></td>
</tr>
<tr class="even">
<td><p>Francis Cheung</p></td>
<td><p><a href="http://blogs.msdn.com/b/francischeung/" class="uri">http://blogs.msdn.com/b/francischeung/</a></p></td>
<td><br />
</td>
</tr>
<tr class="odd">
<td><p>patterns &amp; practices</p></td>
<td><p><a href="http://www.microsoft.com/practices" class="uri">http://www.microsoft.com/practices</a></p></td>
<td><p><a href="https://twitter.com/mspnp">@mspnp</a></p></td>
</tr>
</tbody>
</table>

## Authors and Contributors

Prism was produced by the following individuals:

**patterns & practices Team:**

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Microsoft Corporation</p></td>
<td><p>Blaine Wastell, Bob Brumfield, David Hill, Karl Shifflett, Larry Brader, Michael Puleio, Nelly Delgado</p></td>
</tr>
<tr class="even">
<td><p>Clarius Consulting</p></td>
<td><p>Fernando Simonazzi</p></td>
</tr>
<tr class="odd">
<td><p>Infosys Technologies Ltd</p></td>
<td><p>Mani Krishnaswami, Meenakshi Krishnamoorthi, Rathi Velusamy, Ravindra Varman, Sangeetha Manickam, Sanghamitra Chilla</p></td>
</tr>
<tr class="even">
<td><p>Software Insight</p></td>
<td><p>Brian Noyes</p></td>
</tr>
<tr class="odd">
<td><p>Southworks SRL</p></td>
<td><p>Diego Poza, Fernando Antivero, Geoff Cox, Matias Bonaventura</p></td>
</tr>
<tr class="even">
<td><p>TinaTech, Inc.</p></td>
<td><p>Tina Burden</p></td>
</tr>
<tr class="odd">
<td><p>Modeled Computation</p></td>
<td><p>Sharon Smith, Katie Niemer</p></td>
</tr>
</tbody>
</table>

**Many thanks to the following advisors who provided invaluable assistance:**

Bill Wilder of Fidelity Investments, Clifford Tiltman of Morgan Stanley, Rob Eisenberg of Blue Spire, Norman Headlam, Ward Bell of IdeaBlade, Paul Jackson of CM Group Ltd., John Papa of Microsoft, Julian Dominguez of Clarius Consulting, Ted Neveln of Ballard Indexing Services, Glenn Block of Microsoft, Michael Kenyon of IHS, Inc., Terry Young of PEER Group, Jason Beres of Infragistics, Peter Lindes of The Church of Jesus Christ of Latter-day Saints, Mark Tucker of Neudesic, LLC, David Platt of Rolling Thunder Computing, Steve Gentile of Strategic Data Systems, Markus Egger of EPS Software Corp. and CODE Magazine, Ryan Cromwell of Strategic Data Systems, Todd Neal of McKesson Corp, Dipesh Patel of Fidelity Investments, and David Poll of Microsoft.

Next Topic | Previous Topic | [Home](http://msdn.microsoft.com/en-us/library/gg406140) | [Community](https://compositewpf.codeplex.com/)
