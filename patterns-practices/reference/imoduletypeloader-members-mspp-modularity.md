---
TOCTitle: IModuleTypeLoader Members
Title: 'IModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader'
ms:mtpsurl: 'imoduletypeloader-members-mspp-modularity.md'
---

# IModuleTypeLoader Members

The [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity) type exposes the following members.

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
<td><a href="/patterns-practices/reference/imoduletypeloader-canloadmoduletype-method-mspp-modularity">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity">Ref</a> property to see if the current typeloader will be able to retrieve the moduleInfo.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imoduletypeloader-loadmoduletype-method-mspp-modularity">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the <i>moduleInfo</i>.
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
<td><a href="/patterns-practices/reference/imoduletypeloader-loadmodulecompleted-event-mspp-modularity">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="/patterns-practices/reference/imoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded in the background.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IModuleTypeLoader Interface](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
