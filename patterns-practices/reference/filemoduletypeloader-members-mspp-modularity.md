---
TOCTitle: FileModuleTypeLoader Members
Title: 'FileModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader'
ms:mtpsurl: 'filemoduletypeloader-members-mspp-modularity.md'
---


# FileModuleTypeLoader Members

The [FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>FileModuleTypeLoader()</td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity" data-raw-source="[FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)">FileModuleTypeLoader</a> class.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>FileModuleTypeLoader(IAssemblyResolver)</td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity" data-raw-source="[FileModuleTypeLoader](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)">FileModuleTypeLoader</a> class.
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-canloadmoduletype-method-mspp-modularity" data-raw-source="[CanLoadModuleType](/patterns-practices/reference/filemoduletypeloader-canloadmoduletype-method-mspp-modularity)">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> property starts with &quot;file://&quot;, because this indicates that the file is a local file.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-dispose" data-raw-source="[Dispose()](/patterns-practices/reference/filemoduletypeloader-dispose)">Dispose()</a></td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-dispose-method-boolean-mspp-modularity" data-raw-source="[Dispose(Boolean)](/patterns-practices/reference/filemoduletypeloader-dispose-method-boolean-mspp-modularity)">Dispose(Boolean)</a></td>
<td><div class="summary">
Disposes the associated <a href="/patterns-practices/reference/assemblyresolver-class-mspp-modularity" data-raw-source="[AssemblyResolver](/patterns-practices/reference/assemblyresolver-class-mspp-modularity)">AssemblyResolver</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-loadmoduletype-method-mspp-modularity" data-raw-source="[LoadModuleType](/patterns-practices/reference/filemoduletypeloader-loadmoduletype-method-mspp-modularity)">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the <i>moduleInfo</i>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## Events


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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-loadmodulecompleted-event-mspp-modularity" data-raw-source="[LoadModuleCompleted](/patterns-practices/reference/filemoduletypeloader-loadmodulecompleted-event-mspp-modularity)">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/filemoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity" data-raw-source="[ModuleDownloadProgressChanged](/patterns-practices/reference/filemoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity)">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are loaded in the background.
</div></td>
</tr>
</tbody>
</table>

## See Also

[FileModuleTypeLoader Class](/patterns-practices/reference/filemoduletypeloader-class-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)