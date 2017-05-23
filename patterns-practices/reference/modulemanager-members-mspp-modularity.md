---
TOCTitle: ModuleManager Members
Title: 'ModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430851(v=PandP.50)'
---

Prism Class Library

ModuleManager Members
=====================

The [ModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.">ModuleManager</a></td>
<td><div class="summary">
Initializes an instance of the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager">ModuleManager</a> class.
</div></td>
</tr>
</tbody>
</table>

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
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.dispose">Dispose()()()</a></td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.dispose(system.boolean)">Dispose(Boolean)</a></td>
<td><div class="summary">
Disposes the associated <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a>s.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.handlemoduletypeloadingerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.exception)">HandleModuleTypeLoadingError</a></td>
<td><div class="summary">
Handles any exception occurred in the module typeloading process, logs the error using the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> and throws a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduletypeloadingexception">ModuleTypeLoadingException</a>. This method can be overridden to provide a different behavior.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.loadmodule(system.string)">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.loadmodulesthatarereadyforload">LoadModulesThatAreReadyForLoad</a></td>
<td><div class="summary">
Loads the modules that are not intialized and have their dependencies loaded.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.moduleneedsretrieval(microsoft.practices.prism.modularity.moduleinfo)">ModuleNeedsRetrieval</a></td>
<td><div class="summary">
Checks if the module needs to be retrieved before it's initialized.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.run">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode">WhenAvailable</a> on the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

Properties
----------

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog">ModuleCatalog</a></td>
<td><div class="summary">
The module catalog specified in the constructor.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.moduletypeloaders">ModuleTypeLoaders</a></td>
<td><div class="summary">
Returns the list of registered <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a> instances that will be used to load the types of modules.
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.modulemanager.loadmodulecompleted">LoadModuleCompleted</a></td>
<td><div class="summary">
Raised when a module is loaded or fails to load.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430851.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.modulemanager.moduledownloadprogresschanged">ModuleDownloadProgressChanged</a></td>
<td><div class="summary">
Raised repeatedly to provide progress as modules are loaded in the background.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[ModuleManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
