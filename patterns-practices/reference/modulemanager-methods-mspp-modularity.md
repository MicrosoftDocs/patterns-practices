---
TOCTitle: ModuleManager Methods
Title: 'ModuleManager Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.ModuleManager'
ms:mtpsurl: 'modulemanager-methods-mspp-modularity.md'
---

# ModuleManager Methods

The [ModuleManager](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager) type exposes the following members.

## Methods

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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.dispose">Dispose()()()</a></td>
<td><div class="summary">
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.dispose(system.boolean)">Dispose(Boolean)</a></td>
<td><div class="summary">
Disposes the associated <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imoduletypeloader">IModuleTypeLoader</a>s.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.handlemoduletypeloadingerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.exception)">HandleModuleTypeLoadingError</a></td>
<td><div class="summary">
Handles any exception occurred in the module typeloading process, logs the error using the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> and throws a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduletypeloadingexception">ModuleTypeLoadingException</a>. This method can be overridden to provide a different behavior.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.loadmodule(system.string)">LoadModule</a></td>
<td><div class="summary">
Loads and initializes the module on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.modulecatalog">ModuleCatalog</a> with the name moduleName.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.loadmodulesthatarereadyforload">LoadModulesThatAreReadyForLoad</a></td>
<td><div class="summary">
Loads the modules that are not intialized and have their dependencies loaded.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431063.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.moduleneedsretrieval(microsoft.practices.prism.modularity.moduleinfo)">ModuleNeedsRetrieval</a></td>
<td><div class="summary">
Checks if the module needs to be retrieved before it's initialized.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.run">Run</a></td>
<td><div class="summary">
Initializes the modules marked as <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.initializationmode">WhenAvailable</a> on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager.modulecatalog">ModuleCatalog</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[ModuleManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
