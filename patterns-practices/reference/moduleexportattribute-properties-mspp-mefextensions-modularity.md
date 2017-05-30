---
TOCTitle: ModuleExportAttribute Properties
Title: 'ModuleExportAttribute Properties (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute'
ms:mtpsurl: 'moduleexportattribute-properties-mspp-mefextensions-modularity.md'
---

# ModuleExportAttribute Properties

The [ModuleExportAttribute](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute) type exposes the following members.

## Properties

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd235084">ContractName</a></td>
<td><div class="summary">
Gets the contract name that is used to export the type or member marked with this attribute.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/dd234971">ExportAttribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dd833425">ContractType</a></td>
<td><div class="summary">
Gets the contract type that is exported by the member that this attribute is attached to.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/dd234971">ExportAttribute</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.dependsonmodulenames">DependsOnModuleNames</a></td>
<td><div class="summary">
Gets or sets the contract names of modules this module depends upon.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.initializationmode">InitializationMode</a></td>
<td><div class="summary">
Gets or sets when the module should have Initialize() called.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.modulename">ModuleName</a></td>
<td><div class="summary">
Gets the contract name of the module.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute.moduletype">ModuleType</a></td>
<td><div class="summary">
Gets concrete type of the module being exported. Not typeof(IModule).
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419179.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/sa1bf03e">TypeId</a></td>
<td><div class="summary">
When implemented in a derived class, gets a unique identifier for this <a href="http://msdn.microsoft.com/en-us/library/e8kc3626">Attribute</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e8kc3626">Attribute</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[ModuleExportAttribute Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.moduleexportattribute)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
