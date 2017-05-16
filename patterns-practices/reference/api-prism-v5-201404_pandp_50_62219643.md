---
TOCTitle: ModuleManager Members
Title: 'ModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.ModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430851(v=PandP.50)'
---

Prism Class Library

ModuleManager Members
=====================

Include Protected Members
Include Inherited Members

The [ModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[ModuleManager](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.)
Initializes an instance of the [ModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager) class.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[Dispose()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.dispose)
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[Dispose(Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.dispose(system.boolean))
Disposes the associated [IModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader)s.

![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[HandleModuleTypeLoadingError](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.handlemoduletypeloadingerror(microsoft.practices.prism.modularity.moduleinfo%2csystem.exception))
Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) and throws a [ModuleTypeLoadingException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduletypeloadingexception). This method can be overridden to provide a different behavior.

![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[LoadModule](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.loadmodule(system.string))
Loads and initializes the module on the [ModuleCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog) with the name moduleName.

![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[LoadModulesThatAreReadyForLoad](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.loadmodulesthatarereadyforload)
Loads the modules that are not intialized and have their dependencies loaded.

![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430851.protmethod(en-us,PandP.50).gif "Protected method")
[ModuleNeedsRetrieval](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.moduleneedsretrieval(microsoft.practices.prism.modularity.moduleinfo))
Checks if the module needs to be retrieved before it's initialized.

![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[Run](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.run)
Initializes the modules marked as [WhenAvailable](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode) on the [ModuleCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog).

![](https://msdn.microsoft.com/en-us/Gg430851.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430851.protproperty(en-us,PandP.50).gif "Protected property")
[ModuleCatalog](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.modulecatalog)
The module catalog specified in the constructor.

![](https://msdn.microsoft.com/en-us/Gg430851.pubproperty(en-us,PandP.50).gif "Public property")
[ModuleTypeLoaders](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.modulemanager.moduletypeloaders)
Returns the list of registered [IModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader) instances that will be used to load the types of modules.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430851.pubevent(en-us,PandP.50).gif "Public event")
[LoadModuleCompleted](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.modulemanager.loadmodulecompleted)
Raised when a module is loaded or fails to load.

![](https://msdn.microsoft.com/en-us/Gg430851.pubevent(en-us,PandP.50).gif "Public event")
[ModuleDownloadProgressChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.modulemanager.moduledownloadprogresschanged)
Raised repeatedly to provide progress as modules are loaded in the background.

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
