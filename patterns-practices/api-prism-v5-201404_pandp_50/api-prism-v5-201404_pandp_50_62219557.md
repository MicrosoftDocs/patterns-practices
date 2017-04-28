---
TOCTitle: IModuleTypeLoader Members
Title: 'IModuleTypeLoader Members (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Modularity.IModuleTypeLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430834(v=PandP.50)'
---

Prism Class Library

IModuleTypeLoader Members
=========================

Include Protected Members
Include Inherited Members

The [IModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430834.pubmethod(en-us,PandP.50).gif "Public method")
[CanLoadModuleType](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imoduletypeloader.canloadmoduletype(microsoft.practices.prism.modularity.moduleinfo))
Evaluates the [Ref](https://msdn.microsoft.com/p:microsoft.practices.prism.modularity.moduleinfo.ref) property to see if the current typeloader will be able to retrieve the moduleInfo.

![](https://msdn.microsoft.com/en-us/Gg430834.pubmethod(en-us,PandP.50).gif "Public method")
[LoadModuleType](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imoduletypeloader.loadmoduletype(microsoft.practices.prism.modularity.moduleinfo))
Retrieves the moduleInfo.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430834.pubevent(en-us,PandP.50).gif "Public event")
[LoadModuleCompleted](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imoduletypeloader.loadmodulecompleted)
Raised when a module is loaded or fails to load.

![](https://msdn.microsoft.com/en-us/Gg430834.pubevent(en-us,PandP.50).gif "Public event")
[ModuleDownloadProgressChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.modularity.imoduletypeloader.moduledownloadprogresschanged)
Raised repeatedly to provide progress as modules are downloaded in the background.

See Also
--------

<span id="seeAlsoToggle"></span>
[IModuleTypeLoader Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
