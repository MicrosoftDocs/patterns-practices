---
TOCTitle: MefModuleInitializer Members
Title: 'MefModuleInitializer Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430799(v=PandP.50)'
---

Prism Class Library

MefModuleInitializer Members
============================

The [MefModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer.">MefModuleInitializer</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer">MefModuleInitializer</a> class.
</div></td>
</tr>
</tbody>
</table>

Methods
-------

<span id="methodTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(system.string)">CreateModule(String)</a></td>
<td><div class="summary">
Uses the container to resolve a new <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule">IModule</a> by specifying its <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer">ModuleInitializer</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer.createmodule(microsoft.practices.prism.modularity.moduleinfo)">CreateModule(ModuleInfo)</a></td>
<td><div class="summary">
Uses the container to resolve a new <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule">IModule</a> by specifying its <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a>.
</div>
(Overrides <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(microsoft.practices.prism.modularity.moduleinfo)">ModuleInitializer.CreateModule(ModuleInfo)</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.handlemoduleinitializationerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.string%2csystem.exception)">HandleModuleInitializationError</a></td>
<td><div class="summary">
Handles any exception occurred in the module Initialization process, logs the error using the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> and throws a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializeexception">ModuleInitializeException</a>. This method can be overridden to provide a different behavior.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer">ModuleInitializer</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.initialize(microsoft.practices.prism.modularity.moduleinfo)">Initialize</a></td>
<td><div class="summary">
Initializes the specified module.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer">ModuleInitializer</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------


[MefModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
