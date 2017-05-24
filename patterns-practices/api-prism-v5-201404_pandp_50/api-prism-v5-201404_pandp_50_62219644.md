---
TOCTitle: IModuleManager Members
Title: 'IModuleManager Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430833(v=PandP.50)'
---

Prism Class Library

IModuleManager Members
======================

Include Protected Members
Include Inherited Members

The [IModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430833.pubmethod(en-us,PandP.50).gif "Public method")
[LoadModule](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulemanager.loadmodule(system.string))
Loads and initializes the module on the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog) with the name moduleName.

![](https://msdn.microsoft.com/en-us/Gg430833.pubmethod(en-us,PandP.50).gif "Public method")
[Run](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulemanager.run)
Initializes the modules marked as [WhenAvailable](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.initializationmode) on the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog).

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430833.pubevent(en-us,PandP.50).gif "Public event")
[LoadModuleCompleted](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imodulemanager.loadmodulecompleted)
Raised when a module is loaded or fails to load.

![](https://msdn.microsoft.com/en-us/Gg430833.pubevent(en-us,PandP.50).gif "Public event")
[ModuleDownloadProgressChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imodulemanager.moduledownloadprogresschanged)
Raised repeatedly to provide progress as modules are downloaded.

See Also
--------

<span id="seeAlsoToggle"></span>
[IModuleManager Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
