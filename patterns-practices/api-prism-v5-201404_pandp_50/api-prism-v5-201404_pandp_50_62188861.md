---
TOCTitle: DirectoryModuleCatalog Methods
Title: 'DirectoryModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431037(v=PandP.50)'
---

Prism Class Library

DirectoryModuleCatalog Methods
==============================

Include Protected Members
Include Inherited Members

The [DirectoryModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.directorymodulecatalog) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddGroup](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addgroup(microsoft.practices.prism.modularity.initializationmode%2csystem.string%2cmicrosoft.practices.prism.modularity.moduleinfo%5b%5d))
Creates and adds a [ModuleInfoGroup](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfogroup) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(ModuleInfo)](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(microsoft.practices.prism.modularity.moduleinfo))
Adds a [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(Type, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(system.type%2csystem.string%5b%5d))
Adds a groupless [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(String, String, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2csystem.string%5b%5d))
Adds a groupless [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(Type, InitializationMode, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(system.type%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d))
Adds a groupless [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(String, String, InitializationMode, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d))
Adds a groupless [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule(String, String, String, InitializationMode, array&lt;String&gt;\[\]()\[\])](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.addmodule(system.string%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.modularity.initializationmode%2csystem.string%5b%5d))
Adds a groupless [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the catalog.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[BuildChildDomain](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.directorymodulecatalog.buildchilddomain(system.appdomain))
Creates a new child domain and copies the evidence from a parent domain.

![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[CompleteListWithDependencies](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d))
Returns a list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that contain both the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules, but also all the modules they depend on.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[EnsureCatalogValidated](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.ensurecatalogvalidated)
Ensures that the catalog is validated.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[GetDependentModules](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo))
Return the list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that moduleInfo depends on.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[GetDependentModulesInner](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.getdependentmodulesinner(microsoft.practices.prism.modularity.moduleinfo))
Returns the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) on which the received module dependens on.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[Initialize](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.initialize)
Initializes the catalog, which may load and validate the modules.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[InnerLoad](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.directorymodulecatalog.innerload)
Drives the main logic of building the child domain and searching for the assemblies.

(Overrides [ModuleCatalog..::.InnerLoad()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.innerload).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[Load](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.load)
Loads the catalog if necessary.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[Sort](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.sort(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d))
Sorts a list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;(Of &lt;(ModuleInfo&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d)) to return a sorted list.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431037.pubmethod(en-us,PandP.50).gif "Public method")
[Validate](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validate)
Validates the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[ValidateCrossGroupDependencies](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validatecrossgroupdependencies)
Ensures that there are no dependencies between modules on different groups.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[ValidateDependenciesInitializationMode](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validatedependenciesinitializationmode)
Ensures that there are no modules marked to be loaded [WhenAvailable](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode) depending on modules loaded [OnDemand](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode)

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[ValidateDependencyGraph](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validatedependencygraph)
Ensures that there are no cyclic dependencies.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)
![](https://msdn.microsoft.com/en-us/Gg431037.protmethod(en-us,PandP.50).gif "Protected method")
[ValidateUniqueModules](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validateuniquemodules)
Makes sure all modules have an Unique name.

(Inherited from [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).)

See Also
--------

<span id="seeAlsoToggle"></span>
[DirectoryModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.directorymodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
