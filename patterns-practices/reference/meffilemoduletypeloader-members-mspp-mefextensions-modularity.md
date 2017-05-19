---
TOCTitle: MefFileModuleTypeLoader Members
Title: 'MefFileModuleTypeLoader Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430798(v=PandP.50)'
---

Prism Class Library

MefFileModuleTypeLoader Members
===============================

The [MefFileModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.">MefFileModuleTypeLoader</a></td>
<td><div class="summary">
Initializes a new instance of the MefFileModuleTypeLoader class. This instance is used to load requested module types.
</div></td>
</tr>
</tbody>
</table>

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref">Ref</a> property to see if the current typeloader will be able to retrieve the moduleInfo. Returns true if the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref">Ref</a> property starts with &quot;file://&quot;, because this indicates that the file is a local file.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.loadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the moduleInfo.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

Events
------

<span id="eventTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430798.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are loaded in the background.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[MefFileModuleTypeLoader Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.meffilemoduletypeloader)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
