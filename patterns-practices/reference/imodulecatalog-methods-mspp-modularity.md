---
TOCTitle: IModuleCatalog Methods
Title: 'IModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.IModuleCatalog'
ms:mtpsurl: 'imodulecatalog-methods-mspp-modularity.md'
---

# IModuleCatalog Methods

The [IModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog) type exposes the following members.

## Methods


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.addmodule(microsoft.practices.prism.modularity.moduleinfo)">AddModule</a></td>
<td><div class="summary">
Adds a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns the collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that contain both the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s in modules, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo)">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that moduleInfo depends on.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.initialize">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
</tbody>
</table>

## See Also
[IModuleCatalog Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
