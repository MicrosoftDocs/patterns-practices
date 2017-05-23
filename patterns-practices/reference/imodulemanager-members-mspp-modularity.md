---
TOCTitle: IModuleManager Members
Title: 'IModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430833(v=PandP.50)'
---

Prism Class Library

IModuleManager Members
======================

The [IModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager) type exposes the following members.

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
<td><img src="https://msdn.microsoft.com/en-us/Gg430833.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulemanager.loadmodule(system.string)">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430833.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulemanager.run">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode">WhenAvailable</a> on the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog">ModuleCatalog</a>.
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430833.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imodulemanager.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430833.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imodulemanager.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are downloaded.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[IModuleManager Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
