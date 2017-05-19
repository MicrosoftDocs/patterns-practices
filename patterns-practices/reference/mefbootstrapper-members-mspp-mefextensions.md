---
TOCTitle: MefBootstrapper Members
Title: 'MefBootstrapper Members (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430794(v=PandP.50)'
---

Prism Class Library

MefBootstrapper Members
=======================

The [MefBootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper) type exposes the following members.

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
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.">MefBootstrapper</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper">MefBootstrapper</a> class
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog">ConfigureAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer">ConfigureContainer</a></td>
<td><div class="summary">
Configures the <a href="http://msdn2.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureservicelocator">Bootstrapper..::.ConfigureServiceLocator()()()</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog">CreateAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer">CreateContainer</a></td>
<td><div class="summary">
Creates the <a href="http://msdn2.microsoft.com/en-us/library/dd833553">CompositionContainer</a> that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializemodules">Bootstrapper..::.InitializeModules()()()</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializeshell">Bootstrapper..::.InitializeShell()()()</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes">RegisterBootstrapperProvidedTypes</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn2.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing">RegisterDefaultTypesIfMissing</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn2.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run(system.boolean)">Bootstrapper..::.Run(Boolean)</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

Properties
----------

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a></td>
<td><div class="summary">
Gets or sets the default <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> for the application.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.container">Container</a></td>
<td><div class="summary">
Gets or sets the default <a href="http://msdn2.microsoft.com/en-us/library/dd833553">CompositionContainer</a> for the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.logger">Logger</a></td>
<td><div class="summary">
Gets the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> for the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.modulecatalog">ModuleCatalog</a></td>
<td><div class="summary">
Gets the default <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> for the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.shell">Shell</a></td>
<td><div class="summary">
Gets the shell user interface
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[MefBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
