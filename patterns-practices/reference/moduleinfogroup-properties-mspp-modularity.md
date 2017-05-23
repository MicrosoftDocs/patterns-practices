---
TOCTitle: ModuleInfoGroup Properties
Title: 'ModuleInfoGroup Properties (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431175(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup Properties
==========================

The [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.count">Count</a></td>
<td><div class="summary">
Gets the number of elements contained in the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.initializationmode">InitializationMode</a></td>
<td><div class="summary">
Gets or sets the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.initializationmode">InitializationMode</a> for the whole group. Any <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes that are added after setting this value will also get this <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.initializationmode">InitializationMode</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.isfixedsize">IsFixedSize</a></td>
<td><div class="summary">
Gets a value indicating whether the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a> has a fixed size.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.isreadonly">IsReadOnly</a></td>
<td><div class="summary">
Gets a value indicating whether the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup">ModuleInfoGroup</a> is read-only.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.issynchronized">IsSynchronized</a></td>
<td><div class="summary">
Gets a value indicating whether access to the <a href="http://msdn.microsoft.com/en-us/library/b1ht6113">ICollection</a> is synchronized (thread safe).
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.item(system.int32)">Item</a></td>
<td><div class="summary">
Gets or sets the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> at the specified index.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.ref">Ref</a></td>
<td><div class="summary">
Gets or sets the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref">Ref</a> value for the whole group. Any <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo">ModuleInfo</a> classes that are added after setting this value will also get this <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.ref">Ref</a>. The ref value will also be used by the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager">IModuleManager</a> to determine which <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a> to use. For example, using an &quot;file://&quot; prefix with a valid URL will cause the FileModuleTypeLoader to be used (Only available in the desktop version of CAL).
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431175.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfogroup.syncroot">SyncRoot</a></td>
<td><div class="summary">
Gets an object that can be used to synchronize access to the <a href="http://msdn.microsoft.com/en-us/library/b1ht6113">ICollection</a>.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[ModuleInfoGroup Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
