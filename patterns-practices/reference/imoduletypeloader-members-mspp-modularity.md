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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imoduletypeloader-canloadmoduletype-method-mspp-modularity" data-raw-source="[CanLoadModuleType](/patterns-practices/reference/imoduletypeloader-canloadmoduletype-method-mspp-modularity)">CanLoadModuleType</a></td>
<td><div class="summary">
Evaluates the <a href="/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity" data-raw-source="[Ref](/patterns-practices/reference/moduleinfo-ref-property-mspp-modularity)">Ref</a> property to see if the current typeloader will be able to retrieve the <em>moduleInfo</em>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/imoduletypeloader-loadmoduletype-method-mspp-modularity" data-raw-source="[LoadModuleType](/patterns-practices/reference/imoduletypeloader-loadmoduletype-method-mspp-modularity)">LoadModuleType</a></td>
<td><div class="summary">
Retrieves the <em>moduleInfo</em>.
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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/imoduletypeloader-loadmodulecompleted-event-mspp-modularity" data-raw-source="[LoadModuleCompleted](/patterns-practices/reference/imoduletypeloader-loadmodulecompleted-event-mspp-modularity)">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="/patterns-practices/reference/imoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity" data-raw-source="[ModuleDownloadProgressChanged](/patterns-practices/reference/imoduletypeloader-moduledownloadprogresschanged-event-mspp-modularity)">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded in the background.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IModuleTypeLoader Interface](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  