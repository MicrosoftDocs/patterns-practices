---
TOCTitle: MefModuleManager Methods
Title: 'MefModuleManager Methods (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431012(v=PandP.50)'
---

Prism Class Library

# MefModuleManager Methods

The [MefModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager(v=pandp.50)) type exposes the following members.

## Methods

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[Dispose](https://msdn.microsoft.com/en-us/library/gg405925(v=pandp.50))
Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

(Inherited from [ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50)).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[Dispose(Boolean)](https://msdn.microsoft.com/en-us/library/gg405926(v=pandp.50))
Disposes the associated [IModuleTypeLoader](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduletypeloader(v=pandp.50))s.

(Inherited from [ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50)).)
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[HandleModuleTypeLoadingError](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.handlemoduletypeloadingerror(v=pandp.50))
Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.logging.iloggerfacade(v=pandp.50)) and throws a [ModuleTypeLoadingException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadingexception(v=pandp.50).) This method can be overridden to provide a different behavior.

(Inherited from [ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50)).
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[LoadModule](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.loadmodule(v=pandp.50))
Loads and initializes the module on the [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.modulecatalog(v=pandp.50)) with the name moduleName.

(Inherited from [ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[LoadModulesThatAreReadyForLoad](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulemanager.loadmodulesthatarereadyforload)
Loads the modules that are not intialized and have their dependencies loaded.

(Inherited from [ModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431012.protmethod(en-us,PandP.50).gif "Protected method")
[ModuleNeedsRetrieval](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager.moduleneedsretrieval(v=pandp.50))
Checks if the module needs to be retrieved before it's initialized.

(Overrides [ModuleManager.ModuleNeedsRetrieval(ModuleInfo)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.moduleneedsretrieval(v=pandp.50)).)
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[OnImportsSatisfied](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager.onimportssatisfied(v=pandp.50))
Called when a part's imports have been satisfied and it is safe to use.

![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[Run](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.run(v=pandp.50))
Initializes the modules marked as [WhenAvailable](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.initializationmode(v=pandp.50)) on the [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager.modulecatalog(v=pandp.50)).

(Inherited from [ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50)).)
![](https://msdn.microsoft.com/en-us/Gg431012.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

## See Also

<span id="seeAlsoToggle"></span>
[MefModuleManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
