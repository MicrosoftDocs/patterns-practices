---
TOCTitle: ConfigurationModuleCatalog Properties
Title: 'ConfigurationModuleCatalog Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ConfigurationModuleCatalog'
ms:mtpsurl: 'configurationmodulecatalog-properties-mspp-modularity.md'
---

# ConfigurationModuleCatalog Properties

The [ConfigurationModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.configurationmodulecatalog) type exposes the following members.

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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.grouplessmodules">GrouplessModules</a></td>
<td><div class="summary">
Returns the list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s that are not contained within any <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.groups">Groups</a></td>
<td><div class="summary">
Gets the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>s that have been added to the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.items">Items</a></td>
<td><div class="summary">
Gets the items in the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>. This property is mainly used to add <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>s or <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a>s through XAML.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.modules">Modules</a></td>
<td><div class="summary">
Gets all the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes that are in the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>, regardless if they are within a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a> or not.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.configurationmodulecatalog.store">Store</a></td>
<td><div class="summary">
Gets or sets the store where the configuration is kept.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validated">Validated</a></td>
<td><div class="summary">
Gets or sets a value that remembers whether the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> has been validated already.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[ConfigurationModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.configurationmodulecatalog)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)<br/>