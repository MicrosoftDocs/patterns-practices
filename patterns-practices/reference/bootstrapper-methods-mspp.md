---
TOCTitle: Bootstrapper Methods
Title: 'Bootstrapper Methods (Microsoft.Practices.Prism)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Bootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430970(v=PandP.50)'
---

Prism Class Library

Bootstrapper Methods
====================

The [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper) type exposes the following members.

Methods
-------

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
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430970.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------


[Bootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
