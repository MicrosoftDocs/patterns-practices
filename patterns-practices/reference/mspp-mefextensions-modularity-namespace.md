---
TOCTitle: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.MefExtensions.Modularity'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419040(v=PandP.50)'
---

Prism Class Library

# Microsoft.Practices.Prism.MefExtensions.Modularity Namespace

Classes

<span id="classToggle"></span>
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
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.downloadedpartcatalogcollection(v=pandp.50)">DownloadedPartCatalogCollection</a></td>
<td><div class="summary">
Holds a collection of composable part catalogs keyed by module info.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader(v=pandp.50)">MefFileModuleTypeLoader</a></td>
<td><div class="summary">
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer(v=pandp.50)">ModuleInfo</a> classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library when used with Managed Extensibility Framework.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer(v=pandp.50)">MefModuleInitializer</a></td>
<td><div class="summary">
Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager(v=pandp.50)">MefModuleManager</a></td>
<td><div class="summary">
Component responsible for coordinating the modules' type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-class.gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute(v=pandp.50)">ModuleExportAttribute</a></td>
<td><div class="summary">
An attribute that is applied to describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
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
<td><img src="images/public-interface.gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.imoduleexport(v=pandp.50)">IModuleExport</a></td>
<td><div class="summary">
Describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>
