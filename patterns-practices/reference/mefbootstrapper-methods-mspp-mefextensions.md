---
TOCTitle: MefBootstrapper Methods
Title: 'MefBootstrapper Methods (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'mefbootstrapper-methods-mspp-mefextensions.md'
---
# MefBootstrapper Methods

The [MefBootstrapper](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions) type exposes the following members.

## Methods

||Name|Description|
|-----|-----|-----|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureAggregateCatalog](/patterns-practices/reference/mefbootstrapper-configureaggregatecatalog-method-mspp-mefextensions)|Configures the [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureContainer](/patterns-practices/reference/mefbootstrapper-configurecontainer-method-mspp-mefextensions)|Configures the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureDefaultRegionBehaviors](/patterns-practices/reference/bootstrapper-configuredefaultregionbehaviors-method-mspp)|Configures the [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions). This will be the list of default behaviors that will be added to a region.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureModuleCatalog](/patterns-practices/reference/bootstrapper-configuremodulecatalog-method-mspp)|Configures the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) used by Prism.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp)
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureRegionAdapterMappings](/patterns-practices/reference/bootstrapper-configureregionadaptermappings-method-mspp)|Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[ConfigureServiceLocator](/patterns-practices/reference/mefbootstrapper-configureservicelocator-method-mspp-mefextensions)|Configures the LocatorProvider for the ServiceLocator.(Overrides [Bootstrapper.ConfigureServiceLocator()](/patterns-practices/reference/bootstrapper-configureservicelocator-method-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[CreateAggregateCatalog](/patterns-practices/reference/mefbootstrapper-createaggregatecatalog-method-mspp-mefextensions)|Configures the [AggregateCatalog](/patterns-practices/reference/mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[CreateContainer](/patterns-practices/reference/mefbootstrapper-createcontainer-method-mspp-mefextensions)|Creates the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) that will be used as the default container.|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[CreateLogger](/patterns-practices/reference/bootstrapper-createlogger-method-mspp)|Create the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) used by the bootstrapper.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[CreateModuleCatalog](/patterns-practices/reference/bootstrapper-createmodulecatalog-method-mspp)|Creates the [IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity) used by Prism.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[CreateShell](/patterns-practices/reference/bootstrapper-createshell-method-mspp)|Creates the shell or main window of the application.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)|Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)|Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)|Serves as a hash function for a particular type.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)|Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[InitializeModules](/patterns-practices/reference/mefbootstrapper-initializemodules-method-mspp-mefextensions)|Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog(Overrides [Bootstrapper.InitializeModules()](/patterns-practices/reference/bootstrapper-initializemodules-method-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[InitializeShell](/patterns-practices/reference/mefbootstrapper-initializeshell-method-mspp-mefextensions)|Initializes the shell.(Overrides [Bootstrapper.InitializeShell()](/patterns-practices/reference/bootstrapper-initializeshell-method-mspp).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)|Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[RegisterBootstrapperProvidedTypes](/patterns-practices/reference/mefbootstrapper-registerbootstrapperprovidedtypes-method-mspp-mefextensions)|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[RegisterDefaultTypesIfMissing](/patterns-practices/reference/mefbootstrapper-registerdefaulttypesifmissing-method-mspp-mefextensions)|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.|
|![Protected method](/patterns-practices/reference/images/protmethod.gif)|[RegisterFrameworkExceptionTypes](/patterns-practices/reference/bootstrapper-registerframeworkexceptiontypes-method-mspp)|Registers the [Type](http://msdn2.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the[ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp).(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[Run()](/patterns-practices/reference/bootstrapper-run-method-boolean-mspp)|Runs the bootstrapper process.(Inherited from [Bootstrapper](/patterns-practices/reference/bootstrapper-class-mspp).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[Run(Boolean)](/patterns-practices/reference/mefbootstrapper-run-method-boolean-mspp-mefextensions))|Run the bootstrapper process.(Overrides [Bootstrapper.Run(Boolean)](/patterns-practices/reference/bootstrapper-run-method-boolean-mspp).)|
|![](/patterns-practices/reference/images/public-method.gif "Public method")|[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)|Returns a string that represents the current object.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
## See Also

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)

[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)
MefBootstrapper Methods

The [MefBootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper) type exposes the following members.

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
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog">ConfigureAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer">ConfigureContainer</a></td>
<td><div class="summary">
Configures the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator">Bootstrapper..::.ConfigureServiceLocator()()()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog">CreateAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer">CreateContainer</a></td>
<td><div class="summary">
Creates the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a> that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules">Bootstrapper..::.InitializeModules()()()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell">Bootstrapper..::.InitializeShell()()()</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes">RegisterBootstrapperProvidedTypes</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing">RegisterDefaultTypesIfMissing</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)">Bootstrapper..::.Run(Boolean)</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[MefBootstrapper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions)

