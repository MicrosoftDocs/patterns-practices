---
TOCTitle: MefFileModuleTypeLoader Members
Title: 'MefFileModuleTypeLoader Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader'
ms:mtpsurl: 'meffilemoduletypeloader-members-mspp-mefextensions-modularity.md'
---

# MefFileModuleTypeLoader Members

The [MefFileModuleTypeLoader](/patterns-practices/reference/meffilemoduletypeloader-class-mspp-mefextensions-modularity) type exposes the following members.

## Constructors

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>MefFileModuleTypeLoader</td>
<td>Initializes a new instance of the MefFileModuleTypeLoader class. This instance is used to load requested module types.</td>
</tr>
</tbody>
</table>

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/meffilemoduletypeloader-canloadmoduletype-method-mspp-mefextensions-modularity" data-raw-source="[CanLoadModuleType](/patterns-practices/reference/meffilemoduletypeloader-canloadmoduletype-method-mspp-mefextensions-modularity)">CanLoadModuleType</a></td>
<td>Evaluates the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> property to see if the current typeloader will be able to retrieve the <i>moduleInfo</i>. Returns true if the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> property starts with &quot;file://&quot;, because this indicates that the file is a local file.</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td>Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td>Serves as a hash function for a particular type.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td>Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/meffilemoduletypeloader-loadmoduletype-method-mspp-mefextensions-modularity" data-raw-source="[LoadModuleType](/patterns-practices/reference/meffilemoduletypeloader-loadmoduletype-method-mspp-mefextensions-modularity)">LoadModuleType</a></td>
<td>Retrieves the <i>moduleInfo</i>.</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td>Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td>Returns a string that represents the current object.
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## Events

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/meffilemoduletypeloader-loadmodulecompleted-event-mspp-mefextensions-modularity" data-raw-source="[LoadModuleCompleted](/patterns-practices/reference/meffilemoduletypeloader-loadmodulecompleted-event-mspp-mefextensions-modularity)">LoadModuleCompleted</a></td>
<td>Raised when a module is loaded or fails to load.</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/meffilemoduletypeloader-moduledownloadprogresschanged-event-mspp-mefextensions-modularity" data-raw-source="[ModuleDownloadProgressChanged](/patterns-practices/reference/meffilemoduletypeloader-moduledownloadprogresschanged-event-mspp-mefextensions-modularity)">ModuleDownloadProgressChanged</a></td>
<td>Raised repeatedly to provide progress as modules are loaded in the background.</td>
</tr>
</tbody>
</table>

## See Also

[MefFileModuleTypeLoader Class](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
