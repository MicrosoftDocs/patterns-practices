---
TOCTitle: ModularityException Methods
Title: 'ModularityException Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ModularityException'
ms:mtpsurl: 'modularityexception-methods-mspp-modularity.md'
---

Prism Class Library

ModularityException Methods
===========================

The [ModularityException](modularityexception-class-mspp-modularity.md) type exposes the following members.

Methods
-------

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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431048.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/49kcee3b">GetBaseException</a></td>
<td><div class="summary">
When overridden in a derived class, returns the <a href="http://msdn.microsoft.com/en-us/library/c18k6c59">Exception</a> that is the root cause of one or more subsequent exceptions.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/c18k6c59">Exception</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modularityexception.getobjectdata(system.runtime.serialization.serializationinfo%2csystem.runtime.serialization.streamingcontext)">GetObjectData</a></td>
<td><div class="summary">
Sets the <a href="http://msdn.microsoft.com/en-us/library/a9b6042e">SerializationInfo</a> with information about the exception.
</div>
(Overrides <a href="http://msdn.microsoft.com/en-us/library/fwb1489e">Exception..::.GetObjectData(SerializationInfo, StreamingContext)</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/44zb316t">GetType</a></td>
<td><div class="summary">
Gets the runtime type of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/c18k6c59">Exception</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431048.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/es4y6f7e">ToString</a></td>
<td><div class="summary">
Creates and returns a string representation of the current exception.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/c18k6c59">Exception</a>.)</td>
</tr>
</tbody>
</table>

Extension Methods
-----------------

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
<td><img src="https://msdn.microsoft.com/en-us/Gg431048.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions.getrootexception(system.exception)">GetRootException</a></td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------


[ModularityException Class](modularityexception-class-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
