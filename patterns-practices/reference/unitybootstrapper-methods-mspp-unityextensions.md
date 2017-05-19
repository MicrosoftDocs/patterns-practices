---
TOCTitle: UnityBootstrapper Methods
Title: 'UnityBootstrapper Methods (Microsoft.Practices.Prism.UnityExtensions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.UnityExtensions.UnityBootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431137(v=PandP.50)'
---

Prism Class Library

UnityBootstrapper Methods
=========================


The [UnityBootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.unityextensions.unitybootstrapper) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureContainer](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.configurecontainer)
Configures the IUnityContainer. May be overwritten in a derived class to add specific type mappings required by the application.

![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors)
Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory). This will be the list of default behaviors that will be added to a region.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuremodulecatalog)
Configures the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureregionadaptermappings)
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureServiceLocator](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.configureservicelocator)
Configures the LocatorProvider for the ServiceLocator.

(Overrides [Bootstrapper..::.ConfigureServiceLocator()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureservicelocator).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[CreateContainer](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.createcontainer)
Creates the IUnityContainer that will be used as the default container.

![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[CreateLogger](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createlogger)
Create the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createmodulecatalog)
Creates the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[CreateShell](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createshell)
Creates the shell or main window of the application.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeModules](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.initializemodules)
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog

(Overrides [Bootstrapper..::.InitializeModules()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializemodules).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeShell](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializeshell)
Initializes the shell.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.registerframeworkexceptiontypes)
Registers in the IUnityContainer the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions).

(Overrides [Bootstrapper..::.RegisterFrameworkExceptionTypes()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes).)
![](https://msdn.microsoft.com/en-us/Gg431137.protmethod(en-us,PandP.50).gif "Protected method")
[RegisterTypeIfMissing](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.registertypeifmissing(system.type%2csystem.type%2csystem.boolean))
Registers a type in the container only if that type was not already registered.

![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[Run()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run)
Runs the bootstrapper process.

(Inherited from [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper).)
![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[Run(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.unityextensions.unitybootstrapper.run(system.boolean))
Run the bootstrapper process.

(Overrides [Bootstrapper..::.Run(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run(system.boolean)).)
![](https://msdn.microsoft.com/en-us/Gg431137.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

See Also
--------

<span id="seeAlsoToggle"></span>
[UnityBootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.unityextensions.unitybootstrapper)

[Microsoft.Practices.Prism.UnityExtensions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.unityextensions)