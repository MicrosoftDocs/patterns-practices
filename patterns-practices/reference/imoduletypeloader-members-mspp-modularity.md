---
TOCTitle: IModuleTypeLoader Members
Title: 'IModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader'
ms:mtpsurl: 'imoduletypeloader-members-mspp-modularity.md'
---

# IModuleTypeLoader Members

The [IModuleTypeLoader](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader) type exposes the following members.

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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.ref">Ref</a> property to see if the current typeloader will be able to retrieve the moduleInfo.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.loadmoduletype(microsoft.practices.prism.modularity.moduleinfo)">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the moduleInfo.
</div></td>
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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded in the background.
</div></td>
</tr>
</tbody>
</table>

## See Also
[IModuleTypeLoader Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
