---
TOCTitle: IModuleCatalog Members
Title: 'IModuleCatalog Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleCatalog'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430831(v=PandP.50)'
---

Prism Class Library

IModuleCatalog Members
======================

The [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430831.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.addmodule(microsoft.practices.prism.modularity.moduleinfo)">AddModule</a></td>
<td><div class="summary">
Adds a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430831.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns the collection of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that contain both the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s in modules, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430831.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo)">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that moduleInfo depends on.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430831.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.initialize">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
</tbody>
</table>

Properties
----------

<span id="propertyTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430831.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.imodulecatalog.modules">Modules</a></td>
<td><div class="summary">
Gets all the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes that are in the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[IModuleCatalog Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
