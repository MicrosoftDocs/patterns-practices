---
TOCTitle: ModuleState Enumeration
Title: 'ModuleState Enumeration (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleState'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431506(v=PandP.50)'
---

Prism Class Library

ModuleState Enumeration
=======================

Defines the states a [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) can be in, with regards to the module loading and initialization process.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public enum ModuleStatePublic Enumeration ModuleState

Members
-------

<span id="membersToggle"></span>
|     | Member name            | Value | Description                                                                                                                                                                                                                                                                         |
|-----|------------------------|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     | NotStarted             | 0     | Initial state for [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)s. The [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) is defined, but it has not been loaded, retrieved or initialized yet. |
|     | LoadingTypes           | 1     | The assembly that contains the type of the module is currently being loaded by an instance of a [IModuleTypeLoader](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduletypeloader).                                                                           |
|     | ReadyForInitialization | 2     | The assembly that holds the Module is present. This means the type of the [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) can be instantiated and initialized.                                                                                 |
|     | Initializing           | 3     | The module is currently Initializing, by the [IModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduleinitializer)                                                                                                                             |
|     | Initialized            | 4     | The module is initialized and ready to be used.                                                                                                                                                                                                                                     |

See Also
--------


[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
