---
TOCTitle: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.MefExtensions.Modularity'
ms:mtpsurl: 'mspp-mefextensions-modularity-namespace.md'
---


# Microsoft.Practices.Prism.MefExtensions.Modularity Namespace

Classes


<table>

<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td>[DownloadedPartCatalogCollection](/patterns-practices/reference/downloadedpartcatalogcollection-class-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Holds a collection of composable part catalogs keyed by module info.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td>[MefFileModuleTypeLoader](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if [ModuleInfo](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity) classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library when used with Managed Extensibility Framework.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td>[MefModuleInitializer](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td>[MefModuleManager](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Component responsible for coordinating the modules' type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td>[ModuleExportAttribute](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)</td>
<td><div class="summary">
An attribute that is applied to describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>

## Interfaces


<table>

<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public interface](/images/public-interface.gif)</td>
<td>[IModuleExport](/patterns-practices/reference/imoduleexport-interface-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>
