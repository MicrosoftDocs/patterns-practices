---
TOCTitle: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace'
Title: 'Microsoft.Practices.Prism.MefExtensions.Modularity Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.MefExtensions.Modularity'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419040(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.MefExtensions.Modularity Namespace
============================================================

 

Classes
-------

<span id="classToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.downloadedpartcatalogcollection">DownloadedPartCatalogCollection</a></td>
<td><div class="summary">
Holds a collection of composable part catalogs keyed by module info.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader">MefFileModuleTypeLoader</a></td>
<td><div class="summary">
Loads modules from an arbitrary location on the filesystem. This typeloader is only called if <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes have a Ref parameter that starts with &quot;file://&quot;. This class is only used on the Desktop version of the Prism Library when used with Managed Extensibility Framework.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer">MefModuleInitializer</a></td>
<td><div class="summary">
Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmodulemanager">MefModuleManager</a></td>
<td><div class="summary">
Component responsible for coordinating the modules' type loading and module initialization process.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.moduleexportattribute">ModuleExportAttribute</a></td>
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
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419040.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.imoduleexport">IModuleExport</a></td>
<td><div class="summary">
Describe the Managed Extensibility Framework export of an IModule.
</div></td>
</tr>
</tbody>
</table>
