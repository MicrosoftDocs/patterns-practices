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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd235084" data-raw-source="[ContractName](http://msdn.microsoft.com/en-us/library/dd235084)">ContractName</a></td>
<td><div class="summary">
Gets the contract name that is used to export the type or member marked with this attribute.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/dd234971" data-raw-source="[ExportAttribute](http://msdn.microsoft.com/en-us/library/dd234971)">ExportAttribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd833425" data-raw-source="[ContractType](http://msdn.microsoft.com/en-us/library/dd833425)">ContractType</a></td>
<td><div class="summary">
Gets the contract type that is exported by the member that this attribute is attached to.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/dd234971" data-raw-source="[ExportAttribute](http://msdn.microsoft.com/en-us/library/dd234971)">ExportAttribute</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleexportattribute-dependsonmodulenames-property-mspp-mefextensions-modularity" data-raw-source="[DependsOnModuleNames](/patterns-practices/reference/moduleexportattribute-dependsonmodulenames-property-mspp-mefextensions-modularity)">DependsOnModuleNames</a></td>
<td><div class="summary">
Gets or sets the contract names of modules this module depends upon.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleexportattribute-initializationmode-property-mspp-mefextensions-modularity" data-raw-source="[InitializationMode](/patterns-practices/reference/moduleexportattribute-initializationmode-property-mspp-mefextensions-modularity)">InitializationMode</a></td>
<td><div class="summary">
Gets or sets when the module should have Initialize() called.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleexportattribute-modulename-property-mspp-mefextensions-modularity" data-raw-source="[ModuleName](/patterns-practices/reference/moduleexportattribute-modulename-property-mspp-mefextensions-modularity)">ModuleName</a></td>
<td><div class="summary">
Gets the contract name of the module.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/moduleexportattribute-moduletype-property-mspp-mefextensions-modularity" data-raw-source="[ModuleType](/patterns-practices/reference/moduleexportattribute-moduletype-property-mspp-mefextensions-modularity)">ModuleType</a></td>
<td><div class="summary">
Gets concrete type of the module being exported. Not typeof(IModule).
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/sa1bf03e" data-raw-source="[TypeId](http://msdn.microsoft.com/en-us/library/sa1bf03e)">TypeId</a></td>
<td><div class="summary">
When implemented in a derived class, gets a unique identifier for this <a href="http://msdn.microsoft.com/en-us/library/e8kc3626" data-raw-source="[Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626)">Attribute</a></a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e8kc3626" data-raw-source="[Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626)">Attribute</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[ModuleExportAttribute Class](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
