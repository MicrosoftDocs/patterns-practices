---
TOCTitle: ModuleExportAttribute Members
Title: 'ModuleExportAttribute Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute'
ms:mtpsurl: 'moduleexportattribute-members-mspp-mefextensions-modularity.md'
---

# ModuleExportAttribute Members

The [ModuleExportAttribute](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity) type exposes the following members.

## Constructors

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
<td>ModuleExportAttribute(Type)</td>
<td><div class="summary">
Initializes a new instance of the [ModuleExportAttribute](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity) class.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ModuleExportAttribute(String, Type)</td>
<td><div class="summary">
Initializes a new instance of the [ModuleExportAttribute](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity) class.
</div></td>
</tr>
</tbody>
</table>

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
<td>[Equals](http://msdn.microsoft.com/en-us/library/09ds241w)</td>
<td><div class="summary">
Returns a value that indicates whether this instance is equal to a specified object.
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/365e1bxs)</td>
<td><div class="summary">
Returns the hash code for this instance.
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[IsDefaultAttribute](http://msdn.microsoft.com/en-us/library/tbkb5x6t)</td>
<td><div class="summary">
When overridden in a derived class, indicates whether the value of this instance is the default value for the derived class.
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Match](http://msdn.microsoft.com/en-us/library/wy7chz44)</td>
<td><div class="summary">
When overridden in a derived class, returns a value that indicates whether this instance equals a specified object.
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>[DependsOnModuleNames](https://review.docs.microsoft.com/patterns-practices/reference/imoduleexport-dependsonmodulenames-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets the contract names of modules this module depends upon.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[InitializationMode](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-initializationmode-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets or sets when the module should have Initialize() called.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleName](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-modulename-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets the contract name of the module.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[ModuleType](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-moduletype-property-mspp-mefextensions-modularity)</td>
<td><div class="summary">
Gets concrete type of the module being exported. Not typeof(IModule).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[TypeId](http://msdn.microsoft.com/en-us/library/sa1bf03e)</td>
<td><div class="summary">
When implemented in a derived class, gets a unique identifier for this [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).
</div>
(Inherited from [Attribute](http://msdn.microsoft.com/en-us/library/e8kc3626).)</td>
</tr>
</tbody>
</table>

## See Also

[ModuleExportAttribute Class](https://review.docs.microsoft.com/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://review.docs.microsoft.com/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  