---
TOCTitle: IModuleCatalog Members
Title: 'IModuleCatalog Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleCatalog'
ms:mtpsurl: 'imodulecatalog-members-mspp-modularity.md'
---

# IModuleCatalog Members

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity">AddModule</a></td>
<td><div class="summary">
Adds a <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> to the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imodulecatalog-completelistwithdependencies-method-mspp-modularity">CompleteListWithDependencies</a></td>
<td><div class="summary">
Returns the collection of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s that contain both the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s in modules, but also all the modules they depend on.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imodulecatalog-getdependentmodules-method-mspp-modularity">GetDependentModules</a></td>
<td><div class="summary">
Return the list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>s that moduleInfo depends on.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imodulecatalog-initialize-method-mspp-modularity">Initialize</a></td>
<td><div class="summary">
Initializes the catalog, which may load and validate the modules.
</div></td>
</tr>
</tbody>
</table>

## Properties


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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/imodulecatalog-modules-property-mspp-modularity">Modules</a></td>
<td><div class="summary">
Gets all the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> classes that are in the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IModuleCatalog Interface](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>