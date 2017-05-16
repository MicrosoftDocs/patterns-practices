---
TOCTitle: IModuleCatalog Methods
Title: 'IModuleCatalog Methods (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Modularity.IModuleCatalog'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431043(v=PandP.50)'
---

Prism Class Library

IModuleCatalog Methods
======================

Include Protected Members
Include Inherited Members

The [IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431043.pubmethod(en-us,PandP.50).gif "Public method")
[AddModule](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.addmodule(microsoft.practices.prism.modularity.moduleinfo))
Adds a [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) to the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).

![](https://msdn.microsoft.com/en-us/Gg431043.pubmethod(en-us,PandP.50).gif "Public method")
[CompleteListWithDependencies](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.completelistwithdependencies(system.collections.generic.ienumerable%7bmicrosoft.practices.prism.modularity.moduleinfo%7d))
Returns the collection of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that contain both the [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s in modules, but also all the modules they depend on.

![](https://msdn.microsoft.com/en-us/Gg431043.pubmethod(en-us,PandP.50).gif "Public method")
[GetDependentModules](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo))
Return the list of [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s that moduleInfo depends on.

![](https://msdn.microsoft.com/en-us/Gg431043.pubmethod(en-us,PandP.50).gif "Public method")
[Initialize](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.initialize)
Initializes the catalog, which may load and validate the modules.

See Also
--------

<span id="seeAlsoToggle"></span>
[IModuleCatalog Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
