---
TOCTitle: IModuleCatalog Methods
Title: 'IModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.IModuleCatalog'
ms:mtpsurl: 'imodulecatalog-methods-mspp-modularity.md'
---

# IModuleCatalog Methods

The [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity" data-raw-source="[AddModule](/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity)">AddModule</a></td>
<td><div class="summary">
Adds a <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> to the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imodulecatalog-completelistwithdependencies-method-mspp-modularity" data-raw-source="[CompleteListWithDependencies](/patterns-practices/reference/imodulecatalog-completelistwithdependencies-method-mspp-modularity)">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns the collection of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s that contain both the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s in <i>modules</i>, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imodulecatalog-getdependentmodules-method-mspp-modularity" data-raw-source="[GetDependentModules](/patterns-practices/reference/imodulecatalog-getdependentmodules-method-mspp-modularity)">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s that <i>moduleInfo</i> depends on.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imodulecatalog-initialize-method-mspp-modularity" data-raw-source="[Initialize](/patterns-practices/reference/imodulecatalog-initialize-method-mspp-modularity)">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IModuleCatalog Interface](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  