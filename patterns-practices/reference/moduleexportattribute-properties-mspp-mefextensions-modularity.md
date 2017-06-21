---
TOCTitle: ModuleExportAttribute Properties
Title: 'ModuleExportAttribute Properties (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute'
ms:mtpsurl: 'moduleexportattribute-properties-mspp-mefextensions-modularity.md'
---

# ModuleExportAttribute Properties

The [ModuleExportAttribute](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity) type exposes the following members.

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
<td>[ContractName](http://msdn.microsoft.com/en-us/library/dd235084)</td>
<td><div class="summary">
Gets the contract name that is used to export the type or member marked with this attribute.
</div>
(Inherited from [ExportAttribute](http://msdn.microsoft.com/en-us/library/dd234971).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ContractType](http://msdn.microsoft.com/en-us/library/dd833425)</td>
<td><div class="summary">
Gets the contract type that is exported by the member that this attribute is attached to.
</div>
(Inherited from [ExportAttribute](http://msdn.microsoft.com/en-us/library/dd234971).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[DependsOnModuleNames](/patterns-practices/reference/moduleexportattribute-dependsonmodulenames-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets the contract names of modules this module depends upon.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[InitializationMode](/patterns-practices/reference/moduleexportattribute-initializationmode-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets when the module should have Initialize() called.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleName](/patterns-practices/reference/moduleexportattribute-modulename-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets the contract name of the module.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleType](/patterns-practices/reference/moduleexportattribute-moduletype-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets concrete type of the module being exported. Not typeof(IModule).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[TypeId](http://msdn.microsoft.com/en-us/library/sa1bf03e)</td>
<td><div class="summary">
When implemented in a derived class, gets a unique identifier for this [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626)</a>.
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
</tbody>
</table>

## See Also

[ModuleExportAttribute Class](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
