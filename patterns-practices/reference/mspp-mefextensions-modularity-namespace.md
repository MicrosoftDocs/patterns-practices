---
TOCTitle: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.MefExtensions.Modularity'
ms:mtpsurl: 'mspp-mefextensions-modularity-namespace.md'
---


# Microsoft.Practices.Prism.MefExtensions.Modularity Namespace

## Classes

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
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/downloadedpartcatalogcollection-class-mspp-mefextensions-modularity" data-raw-source="[DownloadedPartCatalogCollection](/patterns-practices/reference/downloadedpartcatalogcollection-class-mspp-mefextensions-modularity)">DownloadedPartCatalogCollection</a></td>
<td><div class="summary">
Holds a collection of composable part catalogs keyed by module info.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity" data-raw-source="[MefFileModuleTypeLoader](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity)">MefFileModuleTypeLoader</a></td>
<td><div class="summary">
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if <a href="/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)">ModuleInfo</a> classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library when used with Managed Extensibility Framework.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity" data-raw-source="[MefModuleInitializer](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)">MefModuleInitializer</a></td>
<td><div class="summary">
Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity" data-raw-source="[MefModuleManager](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)">MefModuleManager</a></td>
<td><div class="summary">
Component responsible for coordinating the modules&#39; type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity" data-raw-source="[ModuleExportAttribute](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)">ModuleExportAttribute</a></td>
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
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/imoduleexport-interface-mspp-mefextensions-modularity" data-raw-source="[IModuleExport](/patterns-practices/reference/imoduleexport-interface-mspp-mefextensions-modularity)">IModuleExport</a></td>
<td><div class="summary">
Describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>
