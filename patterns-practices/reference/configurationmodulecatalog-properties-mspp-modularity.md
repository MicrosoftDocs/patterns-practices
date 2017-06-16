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
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[GrouplessModules](/patterns-practices/reference/modulecatalog-grouplessmodules-property-mspp-modularity)</td>
<td><div class="summary">
Returns the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that are not contained within any [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Groups](/patterns-practices/reference/modulecatalog-groups-property-mspp-modularity)</td>
<td><div class="summary">
Gets the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s that have been added to the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Items](/patterns-practices/reference/modulecatalog-items-property-mspp-modularity)</td>
<td><div class="summary">
Gets the items in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity). This property is mainly used to add [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)s or [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s through XAML.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Modules](/patterns-practices/reference/modulecatalog-modules-property-mspp-modularity)</td>
<td><div class="summary">
Gets all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes that are in the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity), regardless if they are within a [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) or not.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Store](/patterns-practices/reference/configurationmodulecatalog-store-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the store where the configuration is kept.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Validated](/patterns-practices/reference/modulecatalog-validated-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets a value that remembers whether the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) has been validated already.
</div>
(Inherited from [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).)</td>
</tr>
</tbody>
</table>

## See Also

[ConfigurationModuleCatalog Class](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  