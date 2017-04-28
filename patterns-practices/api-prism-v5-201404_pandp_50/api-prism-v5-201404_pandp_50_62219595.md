---
TOCTitle: MefModuleInitializer Members
Title: 'MefModuleInitializer Members (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430799(v=PandP.50)'
---

Prism Class Library

MefModuleInitializer Members
============================

Include Protected Members
Include Inherited Members

The [MefModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[MefModuleInitializer](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer.)
Initializes a new instance of the [MefModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer) class.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModule(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(system.string))
Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

(Inherited from [ModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer).)
![](https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif "Protected method")
[CreateModule(ModuleInfo)](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer.createmodule(microsoft.practices.prism.modularity.moduleinfo))
Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

(Overrides [ModuleInitializer..::.CreateModule(ModuleInfo)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.createmodule(microsoft.practices.prism.modularity.moduleinfo)).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[HandleModuleInitializationError](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.handlemoduleinitializationerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.string%2csystem.exception))
Handles any exception occurred in the module Initialization process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) and throws a [ModuleInitializeException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializeexception). This method can be overridden to provide a different behavior.

(Inherited from [ModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[Initialize](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.moduleinitializer.initialize(microsoft.practices.prism.modularity.moduleinfo))
Initializes the specified module.

(Inherited from [ModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer).)
![](https://msdn.microsoft.com/en-us/Gg430799.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430799.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

See Also
--------

<span id="seeAlsoToggle"></span>
[MefModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
