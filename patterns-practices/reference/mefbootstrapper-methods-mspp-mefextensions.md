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

[MefBootstrapper Class](/patterns-practices/reference/mefbootstrapper-class-mspp-mefextensions)<br/>
[Microsoft.Practices.Prism.MefExtensions Namespace](/patterns-practices/reference/mspp-mefextensions-namespace)<br/>MefBootstrapper Methods

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
<td>[ConfigureAggregateCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog)</td>
<td><div class="summary">
Configures the [AggregateCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog) used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer)</td>
<td><div class="summary">
Configures the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors)</td>
<td><div class="summary">
Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory). This will be the list of default behaviors that will be added to a region.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configuremodulecatalog)</td>
<td><div class="summary">
Configures the [IModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog) used by Prism.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureregionadaptermappings)</td>
<td><div class="summary">
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[ConfigureServiceLocator](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator)</td>
<td><div class="summary">
Configures the LocatorProvider for the ServiceLocator.
</div>
(Overrides [Bootstrapper..::.ConfigureServiceLocator()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.configureservicelocator).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateAggregateCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog)</td>
<td><div class="summary">
Configures the [AggregateCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog) used by MEF.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer)</td>
<td><div class="summary">
Creates the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553) that will be used as the default container.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateLogger](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createlogger)</td>
<td><div class="summary">
Create the [ILoggerFacade](https://msdn.microsoft.com/library/microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createmodulecatalog)</td>
<td><div class="summary">
Creates the [IModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog) used by Prism.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateShell](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.createshell)</td>
<td><div class="summary">
Creates the shell or main window of the application.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeModules](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules)</td>
<td><div class="summary">
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog
</div>
(Overrides [Bootstrapper..::.InitializeModules()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializemodules).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InitializeShell](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell)</td>
<td><div class="summary">
Initializes the shell.
</div>
(Overrides [Bootstrapper..::.InitializeShell()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.initializeshell).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterBootstrapperProvidedTypes](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes)</td>
<td><div class="summary">
Helper method for configuring the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RegisterDefaultTypesIfMissing](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing)</td>
<td><div class="summary">
Helper method for configuring the [CompositionContainer](http://msdn.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes)</td>
<td><div class="summary">
Registers the [Type](http://msdn.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.exceptionextensions).
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run)</td>
<td><div class="summary">
Runs the bootstrapper process.
</div>
(Inherited from [Bootstrapper](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Run(Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean))</td>
<td><div class="summary">
Run the bootstrapper process.
</div>
(Overrides [Bootstrapper..::.Run(Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.bootstrapper.run(system.boolean)).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## See Also
[MefBootstrapper Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper)<br/>
[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions)<br/>
