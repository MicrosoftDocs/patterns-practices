---
TOCTitle: MefBootstrapper Methods
Title: 'MefBootstrapper Methods (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'mefbootstrapper-methods-mspp-mefextensions.md'
---
# MefBootstrapper Methods

The [MefBootstrapper](mefbootstrapper-class-mspp-mefextensions) type exposes the following members.

## Methods

||Name|Description|
|-----|-----|-----|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureAggregateCatalog](mefbootstrapper-configureaggregatecatalog-method-mspp-mefextensions)|Configures the [AggregateCatalog](mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureContainer](mefbootstrapper-configurecontainer-method-mspp-mefextensions)|Configures the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureDefaultRegionBehaviors](bootstrapper-configuredefaultregionbehaviors-method-mspp)|Configures the [IRegionBehaviorFactory](iregionbehaviorfactory-interface-mspp-regions). This will be the list of default behaviors that will be added to a region.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureModuleCatalog](bootstrapper-configuremodulecatalog-method-mspp)|Configures the [IModuleCatalog](imodulecatalog-interface-mspp-modularity) used by Prism.(Inherited from [Bootstrapper](bootstrapper-class-mspp)
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureRegionAdapterMappings](bootstrapper-configureregionadaptermappings-method-mspp)|Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[ConfigureServiceLocator](mefbootstrapper-configureservicelocator-method-mspp-mefextensions)|Configures the LocatorProvider for the ServiceLocator.(Overrides [Bootstrapper.ConfigureServiceLocator()](bootstrapper-configureservicelocator-method-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateAggregateCatalog](mefbootstrapper-createaggregatecatalog-method-mspp-mefextensions)|Configures the [AggregateCatalog](mefbootstrapper-aggregatecatalog-property-mspp-mefextensions) used by MEF.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateContainer](mefbootstrapper-createcontainer-method-mspp-mefextensions)|Creates the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) that will be used as the default container.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateLogger](bootstrapper-createlogger-method-mspp)|Create the [ILoggerFacade](iloggerfacade-interface-mspp-logging) used by the bootstrapper.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateModuleCatalog](bootstrapper-createmodulecatalog-method-mspp)|Creates the [IModuleCatalog](imodulecatalog-interface-mspp-modularity) used by Prism.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[CreateShell](bootstrapper-createshell-method-mspp)|Creates the shell or main window of the application.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](images/public-method.gif "Public method")|[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)|Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)|Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](images/public-method.gif "Public method")|[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)|Serves as a hash function for a particular type.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](images/public-method.gif "Public method")|[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)|Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[InitializeModules](mefbootstrapper-initializemodules-method-mspp-mefextensions)|Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog(Overrides [Bootstrapper.InitializeModules()](bootstrapper-initializemodules-method-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[InitializeShell](mefbootstrapper-initializeshell-method-mspp-mefextensions)|Initializes the shell.(Overrides [Bootstrapper.InitializeShell()](bootstrapper-initializeshell-method-mspp).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)|Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[RegisterBootstrapperProvidedTypes](mefbootstrapper-registerbootstrapperprovidedtypes-method-mspp-mefextensions)|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.|
|![](images/public-method.gif "Public method")|[RegisterDefaultTypesIfMissing](mefbootstrapper-registerdefaulttypesifmissing-method-mspp-mefextensions)|Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.|
|![](https://msdn.microsoft.com/en-us/Gg431007.protmethod(en-us,PandP.50).gif "Protected method")|[RegisterFrameworkExceptionTypes](bootstrapper-registerframeworkexceptiontypes-method-mspp)|Registers the [Type](http://msdn2.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the[ExceptionExtensions](exceptionextensions-class-mspp).(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](images/public-method.gif "Public method")|[Run()](bootstrapper-run-method-boolean-mspp)|Runs the bootstrapper process.(Inherited from [Bootstrapper](bootstrapper-class-mspp).)|
|![](images/public-method.gif "Public method")|[Run(Boolean)](mefbootstrapper-run-method-boolean-mspp-mefextensions))|Run the bootstrapper process.(Overrides [Bootstrapper.Run(Boolean)](bootstrapper-run-method-boolean-mspp).)|
|![](images/public-method.gif "Public method")|[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)|Returns a string that represents the current object.(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
## See Also

[MefBootstrapper Class](mefbootstrapper-class-mspp-mefextensions)

[Microsoft.Practices.Prism.MefExtensions Namespace](mspp-mefextensions-namespace)
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
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog">ConfigureAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer">ConfigureContainer</a></td>
<td><div class="summary">
Configures the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors">ConfigureDefaultRegionBehaviors</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory">IRegionBehaviorFactory</a>. This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog">ConfigureModuleCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings">ConfigureRegionAdapterMappings</a></td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator">ConfigureServiceLocator</a></td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator">Bootstrapper..::.ConfigureServiceLocator()()()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog">CreateAggregateCatalog</a></td>
<td><div class="summary">
Configures the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog">AggregateCatalog</a> used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer">CreateContainer</a></td>
<td><div class="summary">
Creates the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a> that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger">CreateLogger</a></td>
<td><div class="summary">
Create the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade">ILoggerFacade</a> used by the bootstrapper.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog">CreateModuleCatalog</a></td>
<td><div class="summary">
Creates the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog">IModuleCatalog</a> used by Prism.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell">CreateShell</a></td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules">InitializeModules</a></td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules">Bootstrapper..::.InitializeModules()()()</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell">InitializeShell</a></td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell">Bootstrapper..::.InitializeShell()()()</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes">RegisterBootstrapperProvidedTypes</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing">RegisterDefaultTypesIfMissing</a></td>
<td><div class="summary">
Helper method for configuring the <a href="http://msdn.microsoft.com/en-us/library/dd833553">CompositionContainer</a>. Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/images/protmethod.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes">RegisterFrameworkExceptionTypes</a></td>
<td><div class="summary">
Registers the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>s of the Exceptions that are not considered root exceptions by the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions">ExceptionExtensions</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run">Run()()()</a></td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper">Bootstrapper</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean)">Run(Boolean)</a></td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)">Bootstrapper..::.Run(Boolean)</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
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

