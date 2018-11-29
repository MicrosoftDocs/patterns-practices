---
TOCTitle: ConfigurationModuleCatalog Properties
Title: 'ConfigurationModuleCatalog Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ConfigurationModuleCatalog'
ms:mtpsurl: 'configurationmodulecatalog-properties-mspp-modularity.md'
---

# ConfigurationModuleCatalog Properties

The [ConfigurationModuleCatalog](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-grouplessmodules-property-mspp-modularity" data-raw-source="[GrouplessModules](/patterns-practices/reference/modulecatalog-grouplessmodules-property-mspp-modularity)">GrouplessModules</a></td>
<td><div class="summary">
Returns the list of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s that are not contained within any <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-groups-property-mspp-modularity" data-raw-source="[Groups](/patterns-practices/reference/modulecatalog-groups-property-mspp-modularity)">Groups</a></td>
<td><div class="summary">
Gets the <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>s that have been added to the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-items-property-mspp-modularity" data-raw-source="[Items](/patterns-practices/reference/modulecatalog-items-property-mspp-modularity)">Items</a></td>
<td><div class="summary">
Gets the items in the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>. This property is mainly used to add <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a>s or <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a>s through XAML.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-modules-property-mspp-modularity" data-raw-source="[Modules](/patterns-practices/reference/modulecatalog-modules-property-mspp-modularity)">Modules</a></td>
<td><div class="summary">
Gets all the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity" data-raw-source="[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)">ModuleInfo</a> classes that are in the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>, regardless if they are within a <a href="/patterns-practices/reference/moduleinfogroup-class-mspp-modularity" data-raw-source="[ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)">ModuleInfoGroup</a> or not.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/configurationmodulecatalog-store-property-mspp-modularity" data-raw-source="[Store](/patterns-practices/reference/configurationmodulecatalog-store-property-mspp-modularity)">Store</a></td>
<td><div class="summary">
Gets or sets the store where the configuration is kept.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/modulecatalog-validated-property-mspp-modularity" data-raw-source="[Validated](/patterns-practices/reference/modulecatalog-validated-property-mspp-modularity)">Validated</a></td>
<td><div class="summary">
Gets or sets a value that remembers whether the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a> has been validated already.
</div>
(Inherited from <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity" data-raw-source="[ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)">ModuleCatalog</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[ConfigurationModuleCatalog Class](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  