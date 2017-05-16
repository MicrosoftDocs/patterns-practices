---
TOCTitle: 'CreateModule Method (ModuleInfo)'
Title: 'ModuleInitializer.CreateModule Method (ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.CreateModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405921(v=PandP.50)'
---

Prism Class Library

ModuleInitializer..::.CreateModule Method (ModuleInfo)
======================================================

Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual IModule CreateModule( ModuleInfo moduleInfo )Protected Overridable Function CreateModule ( moduleInfo As ModuleInfo ) As IModule
#### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity..::.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The module to create.

#### Return Value

Type: [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule)
A new instance of the module specified by moduleInfo.

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer)

[ModuleInitializer Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinitializer)

[CreateModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinitializer.createmodule)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
