---
TOCTitle: Bootstrapper Members
Title: 'Bootstrapper Members (Microsoft.Practices.Prism)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Bootstrapper'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430755(v=PandP.50)'
---

Prism Class Library

Bootstrapper Members
====================

Include Protected Members
Include Inherited Members

The [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[Bootstrapper](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.)
Initializes a new instance of the [Bootstrapper](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper) class

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureDefaultRegionBehaviors](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuredefaultregionbehaviors)
Configures the [IRegionBehaviorFactory](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehaviorfactory). This will be the list of default behaviors that will be added to a region.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configuremodulecatalog)
Configures the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureRegionAdapterMappings](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureregionadaptermappings)
Configures the default region adapter mappings to use in the application, in order to adapt UI controls defined in XAML to use a region and register it automatically. May be overwritten in a derived class to add specific mappings required by the application.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[ConfigureServiceLocator](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.configureservicelocator)
Configures the LocatorProvider for the ServiceLocator.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[CreateLogger](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createlogger)
Create the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) used by the bootstrapper.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModuleCatalog](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createmodulecatalog)
Creates the [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) used by Prism.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[CreateShell](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.createshell)
Creates the shell or main window of the application.

![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeModules](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializemodules)
Initializes the modules. May be overwritten in a derived class to use a custom Modules Catalog

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[InitializeShell](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.initializeshell)
Initializes the shell.

![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430755.protmethod(en-us,PandP.50).gif "Protected method")
[RegisterFrameworkExceptionTypes](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.registerframeworkexceptiontypes)
Registers the [Type](http://msdn2.microsoft.com/en-us/library/42892f65)s of the Exceptions that are not considered root exceptions by the [ExceptionExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.exceptionextensions).

![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[Run()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run)
Runs the bootstrapper process.

![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[Run(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.bootstrapper.run(system.boolean))
Run the bootstrapper process.

![](https://msdn.microsoft.com/en-us/Gg430755.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430755.protproperty(en-us,PandP.50).gif "Protected property")
[Logger](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.logger)
Gets the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) for the application.

![](https://msdn.microsoft.com/en-us/Gg430755.protproperty(en-us,PandP.50).gif "Protected property")
[ModuleCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.modulecatalog)
Gets the default [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) for the application.

![](https://msdn.microsoft.com/en-us/Gg430755.protproperty(en-us,PandP.50).gif "Protected property")
[Shell](https://msdn.microsoft.com/p:microsoft.practices.prism.bootstrapper.shell)
Gets the shell user interface

See Also
--------

<span id="seeAlsoToggle"></span>
[Bootstrapper Class](https://msdn.microsoft.com/t:microsoft.practices.prism.bootstrapper)

[Microsoft.Practices.Prism Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism)
