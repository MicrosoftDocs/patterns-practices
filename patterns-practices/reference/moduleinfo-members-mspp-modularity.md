---
TOCTitle: ModuleInfo Members
Title: 'ModuleInfo Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleInfo'
ms:mtpsurl: 'moduleinfo-members-mspp-modularity.md'
---


# ModuleInfo Members

The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) type exposes the following members.

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
<td>ModuleInfo()</td>
<td><div class="summary">
Initializes a new empty instance of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ModuleInfo(String, String)</td>
<td><div class="summary">
Initializes a new instance of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ModuleInfo(String, String, String[])</td>
<td><div class="summary">
Initializes a new instance of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity).
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
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>