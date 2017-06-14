---
TOCTitle: FileModuleTypeLoader Methods
Title: 'FileModuleTypeLoader Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader'
ms:mtpsurl: 'filemoduletypeloader-methods-mspp-modularity.md'
---

# FileModuleTypeLoader Methods

The [FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity) type exposes the following members.

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
<td>[CanLoadModuleType](/patterns-practices/reference/filemoduletypeloader-canloadmoduletype-method-mspp-modularity)</td>
<td><div class="summary">
Evaluates the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property to see if the current typeloader will be able to retrieve the <i>moduleInfo</i>. Returns true if the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property starts with &quot;file://&quot;, because this indicates that the file is a local file.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Dispose()](/patterns-practices/reference/filemoduletypeloader-dispose)</td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Dispose(Boolean)](/patterns-practices/reference/filemoduletypeloader-dispose-method-boolean-mspp-modularity)</td>
<td><div class="summary">
Disposes the associated [AssemblyResolver](/patterns-practices/reference/assemblyresolver-class-mspp-modularity).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[LoadModuleType](/patterns-practices/reference/filemoduletypeloader-loadmoduletype-method-mspp-modularity)</td>
<td><div class="summary">
Retrieves the <i>moduleInfo</i>.
</div></td>
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

## See Also

[FileModuleTypeLoader Class](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>