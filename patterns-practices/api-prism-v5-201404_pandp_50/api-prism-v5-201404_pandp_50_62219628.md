---
TOCTitle: MefBootstrapper Members
Title: 'MefBootstrapper Members (Microsoft.Practices.Prism.MefExtensions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.MefBootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430794(v=PandP.50)'
---

Prism Class Library

MefBootstrapper Members
=======================

Include Protected Members
Include Inherited Members

The [MefBootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[MefBootstrapper](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.)
Initializes a new instance of the [MefBootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper) class

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureAggregateCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configureaggregatecatalog)
Configures the [AggregateCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog) used by MEF.

![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureContainer](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer)
Configures the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). May be overwritten in a derived class to add specific type mappings required by the application.

![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors)
Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory). This will be the list of default behaviors that will be added to a region.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuremodulecatalog)
Configures the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureregionadaptermappings)
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureServiceLocator](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configureservicelocator)
Configures the LocatorProvider for the ServiceLocator.

(Overrides [Bootstrapper..::.ConfigureServiceLocator()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureservicelocator).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[CreateAggregateCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.createaggregatecatalog)
Configures the [AggregateCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog) used by MEF.

![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[CreateContainer](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.createcontainer)
Creates the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) that will be used as the default container.

![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[CreateLogger](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createlogger)
Create the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createmodulecatalog)
Creates the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[CreateShell](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createshell)
Creates the shell or main window of the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeModules](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.initializemodules)
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog

(Overrides [Bootstrapper..::.InitializeModules()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializemodules).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeShell](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.initializeshell)
Initializes the shell.

(Overrides [Bootstrapper..::.InitializeShell()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializeshell).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[RegisterBootstrapperProvidedTypes](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.registerbootstrapperprovidedtypes)
Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers all the types direct instantiated by the bootstrapper with the container.

![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[RegisterDefaultTypesIfMissing](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.registerdefaulttypesifmissing)
Helper method for configuring the [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553). Registers defaults for all the types necessary for Prism to work, if they are not already registered.

![](https://msdn.microsoft.com/en-us/Gg430794.protmethod(en-us,PandP.50).gif "Protected method")
[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes)
Registers the [Type](http://msdn2.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions).

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[Run()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run)
Runs the bootstrapper process.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[Run(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.run(system.boolean))
Run the bootstrapper process.

(Overrides [Bootstrapper..::.Run(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run(system.boolean)).)
![](https://msdn.microsoft.com/en-us/Gg430794.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif "Protected property")
[AggregateCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog)
Gets or sets the default [AggregateCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.aggregatecatalog) for the application.

![](https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif "Protected property")
[Container](https://msdn.microsoft.com/p:microsoft.practices.prism.mefextensions.mefbootstrapper.container)
Gets or sets the default [CompositionContainer](http://msdn2.microsoft.com/en-us/library/dd833553) for the application.

![](https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif "Protected property")
[Logger](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.logger)
Gets the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) for the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif "Protected property")
[ModuleCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.modulecatalog)
Gets the default [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) for the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg430794.protproperty(en-us,PandP.50).gif "Protected property")
[Shell](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.shell)
Gets the shell user interface

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)

See Also
--------

<span id="seeAlsoToggle"></span>
[MefBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.mefbootstrapper)

[Microsoft.Practices.Prism.MefExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions)
