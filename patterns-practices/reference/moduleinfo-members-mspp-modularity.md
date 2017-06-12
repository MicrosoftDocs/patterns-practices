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
Initializes a new empty instance of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ModuleInfo(String, String)</td>
<td><div class="summary">
Initializes a new instance of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ModuleInfo(String, String, String[])</td>
<td><div class="summary">
Initializes a new instance of <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a>.
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
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
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
<td><a href="/patterns-practices/reference/moduleinfo-dependson-property-mspp-modularity">DependsOn</a></td>
<td><div class="summary">
Gets or sets the list of modules that this module depends upon.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/moduleinfo-initializationmode-property-mspp-modularity">InitializationMode</a></td>
<td><div class="summary">
Specifies on which stage the Module will be initialized.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/moduleinfo-modulename-property-mspp-modularity">ModuleName</a></td>
<td><div class="summary">
Gets or sets the name of the module.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/moduleinfo-moduletype-property-mspp-modularity">ModuleType</a></td>
<td><div class="summary">
Gets or sets the module <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>'s AssemblyQualifiedName.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity">Ref</a></td>
<td><div class="summary">
Reference to the location of the module assembly.
<div>
<h2 id="examples">Examples</h2>
The following are examples of valid <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity">Ref</a> values: file://c:/MyProject/Modules/MyModule.dll for a loose DLL in WPF.
</div>
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/moduleinfo-state-property-mspp-modularity">State</a></td>
<td><div class="summary">
Gets or sets the state of the <a href="/patterns-practices/reference/moduleinfo-class-mspp-modularity">ModuleInfo</a> with regards to the module loading and initialization process.
</div></td>
</tr>
</tbody>
</table>

## See Also

[ModuleInfo Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>