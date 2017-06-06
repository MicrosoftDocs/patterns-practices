---
TOCTitle: IModuleManager Members
Title: 'IModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleManager'
ms:mtpsurl: 'imodulemanager-members-mspp-modularity.md'
---


# IModuleManager Members

The [IModuleManager](/patterns-practices/reference/imodulemanager-interface-mspp-modularity) type exposes the following members.

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
<td><a href="/patterns-practices/reference/imodulemanager-loadmodule-method-mspp-modularity">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/imodulemanager-run-method-mspp-modularity">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="/patterns-practices/reference/initializationmode-enumeration-mspp-modularity">WhenAvailable</a> on the <a href="/patterns-practices/reference/modulecatalog-class-mspp-modularity">ModuleCatalog</a>.
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
<td><a href="/patterns-practices/reference/imodulemanager-loadmodulecompleted-event-mspp-modularity">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="/patterns-practices/reference/imodulemanager-moduledownloadprogresschanged-event-mspp-modularity">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IModuleManager Interface](/patterns-practices/reference/imodulemanager-interface-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
