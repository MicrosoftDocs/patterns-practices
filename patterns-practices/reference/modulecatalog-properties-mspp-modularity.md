---
TOCTitle: ModuleCatalog Properties
Title: 'ModuleCatalog Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleCatalog'
ms:mtpsurl: 'modulecatalog-properties-mspp-modularity.md'
---


# ModuleCatalog Properties

The [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) type exposes the following members.

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
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-grouplessmodules-property-mspp-modularity
">GrouplessModules</a></td>
<td><div class="summary">
Returns the list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity
">ModuleInfo</a>s that are not contained within any <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity
">ModuleInfoGroup</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-groups-property-mspp-modularity
">Groups</a></td>
<td><div class="summary">
Gets the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity
">ModuleInfoGroup</a>s that have been added to the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity
">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-items-property-mspp-modularity
">Items</a></td>
<td><div class="summary">
Gets the items in the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity
">ModuleCatalog</a>. This property is mainly used to add <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity
">ModuleInfoGroup</a>s or <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity
">ModuleInfo</a>s through XAML.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-modules-property-mspp-modularity
">Modules</a></td>
<td><div class="summary">
Gets all the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity
">ModuleInfo</a> classes that are in the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity
">ModuleCatalog</a>, regardless if they are within a <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity
">ModuleInfoGroup</a> or not.
</div></td>
</tr>
<tr class="odd">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td><a href="/patterns-practices/reference/modulecatalog-validated-property-mspp-modularity
">Validated</a></td>
<td><div class="summary">
Gets or sets a value that remembers whether the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity
">ModuleCatalog</a> has been validated already.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>