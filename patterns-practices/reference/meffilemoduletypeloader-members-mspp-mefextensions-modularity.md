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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CanLoadModuleType](/patterns-practices/reference/meffilemoduletypeloader-canloadmoduletype-method-mspp-mefextensions-modularity)</td>
<td>Evaluates the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property to see if the current typeloader will be able to retrieve the <i>moduleInfo</i>. Returns true if the [Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity) property starts with &quot;file://&quot;, because this indicates that the file is a local file.</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td>Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td>Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td>Serves as a hash function for a particular type.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td>Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[LoadModuleType](/patterns-practices/reference/meffilemoduletypeloader-loadmoduletype-method-mspp-mefextensions-modularity)</td>
<td>Retrieves the <i>moduleInfo</i>.</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td>Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td>Returns a string that represents the current object.
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[LoadModuleCompleted](/patterns-practices/reference/meffilemoduletypeloader-loadmodulecompleted-event-mspp-mefextensions-modularity)</td>
<td>Raised when a module is loaded or fails to load.</td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[ModuleDownloadProgressChanged](/patterns-practices/reference/meffilemoduletypeloader-moduledownloadprogresschanged-event-mspp-mefextensions-modularity)</td>
<td>Raised repeatedly to provide progress as modules are loaded in the background.</td>
</tr>
</tbody>
</table>

## See Also

[MefFileModuleTypeLoader Class](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
