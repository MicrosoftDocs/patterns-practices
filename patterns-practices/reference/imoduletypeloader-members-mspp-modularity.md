---
TOCTitle: IModuleTypeLoader Members
Title: 'IModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430834(v=PandP.50)'
---

Prism Class Library

IModuleTypeLoader Members
=========================

The [IModuleTypeLoader](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref">Ref</a> property to see if the current typeloader will be able to retrieve the moduleInfo.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.loadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the moduleInfo.
</div></td>
</tr>
</tbody>
</table>

Events
------

<span id="eventTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430834.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430834.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded in the background.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[IModuleTypeLoader Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
