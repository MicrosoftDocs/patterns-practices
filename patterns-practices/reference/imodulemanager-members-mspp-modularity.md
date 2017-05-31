---
TOCTitle: IModuleManager Members
Title: 'IModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleManager'
ms:mtpsurl: 'imodulemanager-members-mspp-modularity.md'
---

# IModuleManager Members

The [IModuleManager](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager) type exposes the following members.

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
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager.loadmodule(system.string)">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager.run">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.initializationmode">WhenAvailable</a> on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
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
<td>![Public event](/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/images/pubevent.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded.
</div></td>
</tr>
</tbody>
</table>

## See Also
[IModuleManager Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
