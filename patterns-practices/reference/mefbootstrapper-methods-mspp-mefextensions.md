---
TOCTitle: MefBootstrapper Methods
Title: 'MefBootstrapper Methods (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431007(v=PandP.50)'
---


# MefBootstrapper Methods

The [MefBootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper(v=pandp.50)) type exposes the following members.

## Methods

||Name|Description|
|-----|-----|-----|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureAggregateCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog(v=pandp.50))|Configures the [AggregateCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog(v=pandp.50)) used by MEF.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureContainer](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer(v=pandp.50))|Configures the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors(v=pandp.50))|Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionbehaviorfactory(v=pandp.50)). This will be the list of default behaviors that will be added to a region.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog(v=pandp.50))|Configures the [IModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalog(v=pandp.50)) used by Prism.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50))
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings(v=pandp.50))|Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureServiceLocator](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator(v=pandp.50))|Configures the LocatorProvider for the ServiceLocator.(Overrides [Bootstrapper.ConfigureServiceLocator()](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.configureservicelocator(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateAggregateCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog(v=pandp.50))|Configures the [AggregateCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog(v=pandp.50)) used by MEF.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateContainer](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer(v=pandp.50))|Creates the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) that will be used as the default container.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateLogger](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.createlogger(v=pandp.50))|Create the [ILoggerFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.logging.iloggerfacade(v=pandp.50)) used by the bootstrapper.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.createmodulecatalog(v=pandp.50))|Creates the [IModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalog(v=pandp.50)) used by Prism.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateShell](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.createshell(v=pandp.50))|Creates the shell or main window of the application.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](images/public-method.gif "Public method")|[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)|Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)|Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](images/public-method.gif "Public method")|[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)|Serves as a hash function for a particular type.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](images/public-method.gif "Public method")|[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)|Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[InitializeModules](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules(v=pandp.50))|Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog(Overrides [Bootstrapper.InitializeModules()](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.initializemodules(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[InitializeShell](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell(v=pandp.50))|Initializes the shell.(Overrides [Bootstrapper.InitializeShell()](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.initializeshell(v=pandp.50)).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)|Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[RegisterBootstrapperProvidedTypes](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes(v=pandp.50))|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.|
|![](images/public-method.gif "Public method")|[RegisterDefaultTypesIfMissing](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing(v=pandp.50))|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes(v=pandp.50))|Registers the [Type](http://msdn2.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the[ExceptionExtensions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.exceptionextensions(v=pandp.50)).(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](images/public-method.gif "Public method")|[Run()](https://msdn.microsoft.com/en-us/library/gg405739(v=pandp.50))|Runs the bootstrapper process.(Inherited from [Bootstrapper](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.bootstrapper(v=pandp.50)).)|
|![](images/public-method.gif "Public method")|[Run(Boolean)](https://msdn.microsoft.com/en-us/library/gg405830(v=pandp.50)))|Run the bootstrapper process.(Overrides [Bootstrapper.Run(Boolean)](https://msdn.microsoft.com/en-us/library/gg405740(v=pandp.50)).)|
|![](images/public-method.gif "Public method")|[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)|Returns a string that represents the current object.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)


## See Also

[MefBootstrapper Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.mefbootstrapper(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions(v=pandp.50))
=======
Prism Class Library

MefBootstrapper Methods
=======================

The [MefBootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper) type exposes the following members.

Methods
-------

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
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog">ConfigureAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer">ConfigureContainer</a></td>
<td><div class="summary">
Configures the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator">Bootstrapper..::.ConfigureServiceLocator()()()</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog">CreateAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer">CreateContainer</a></td>
<td><div class="summary">
Creates the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a> that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules">Bootstrapper..::.InitializeModules()()()</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell">Bootstrapper..::.InitializeShell()()()</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes">RegisterBootstrapperProvidedTypes</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing">RegisterDefaultTypesIfMissing</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)">Bootstrapper..::.Run(Boolean)</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
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


[MefBootstrapper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions)

