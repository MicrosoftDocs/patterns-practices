---
TOCTitle: ModuleInfo Properties
Title: 'ModuleInfo Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleInfo'
ms:mtpsurl: 'moduleinfo-properties-mspp-modularity.md'
---

# ModuleInfo Properties

The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) type exposes the following members.

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
<td>[DependsOn](/patterns-practices/reference/moduleinfo-dependson-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the list of modules that this module depends upon.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[InitializationMode](/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity)</td>
<td><div class="summary">
Specifies on which stage the Module will be initialized.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleName](/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the name of the module.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleType](/patterns-practices/reference/moduleinfo-moduletype-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the module [Type](http://msdn.microsoft.com/en-us/library/42892f65)'s AssemblyQualifiedName.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)</td>
<td><div class="summary">
Reference to the location of the module assembly.
<div>
<h2 id="examples">Examples</h2>
The following are examples of valid [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) values: file://c:/MyProject/Modules/MyModule.dll for a loose DLL in WPF.
</div>
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[State](/patterns-practices/reference/moduleinfo-state-property-mspp-modularity)</td>
<td><div class="summary">
Gets or sets the state of the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  