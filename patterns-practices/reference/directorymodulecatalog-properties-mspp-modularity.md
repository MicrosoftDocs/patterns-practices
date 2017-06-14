---
TOCTitle: DirectoryModuleCatalog Properties
Title: 'DirectoryModuleCatalog Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog'
ms:mtpsurl: 'directorymodulecatalog-properties-mspp-modularity.md'
---

# DirectoryModuleCatalog Properties

The [DirectoryModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.directorymodulecatalog) type exposes the following members.

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
<td>[GrouplessModules](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.grouplessmodules)</td>
<td><div class="summary">
Returns the list of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)s that are not contained within any [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup).
</div>
(Inherited from [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Groups](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.groups)</td>
<td><div class="summary">
Gets the [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)s that have been added to the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).
</div>
(Inherited from [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Items](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.items)</td>
<td><div class="summary">
Gets the items in the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog). This property is mainly used to add [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)s or [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)s through XAML.
</div>
(Inherited from [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModulePath](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.directorymodulecatalog.modulepath)</td>
<td><div class="summary">
Directory containing modules to search for.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Modules](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.modules)</td>
<td><div class="summary">
Gets all the [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) classes that are in the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog), regardless if they are within a [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup) or not.
</div>
(Inherited from [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[Validated](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validated)</td>
<td><div class="summary">
Gets or sets a value that remembers whether the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) has been validated already.
</div>
(Inherited from [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog).)</td>
</tr>
</tbody>
</table>

## See Also
[DirectoryModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.directorymodulecatalog)  
[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)  