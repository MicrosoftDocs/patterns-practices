---
TOCTitle: ModuleState Enumeration
Title: 'ModuleState Enumeration (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleState'
ms:mtpsurl: 'modulestate-enumeration-mspp-modularity.md'
---


# ModuleState Enumeration

Defines the states a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) can be in, with regards to the module loading and initialization process.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public enum ModuleState
```

```VB
'Declaration
Public Enumeration ModuleState
```

## Members

| | Member name | Value | Description |
|---|---|---|---|
|     | NotStarted             | 0     | Initial state for [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s. The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) is defined, but it has not been loaded, retrieved or initialized yet. |
|     | LoadingTypes           | 1     | The assembly that contains the type of the module is currently being loaded by an instance of a [IModuleTypeLoader](/patterns-practices/reference/imoduletypeloader-interface-mspp-modularity).                                                                           |
|     | ReadyForInitialization | 2     | The assembly that holds the Module is present. This means the type of the [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) can be instantiated and initialized.                                                                                 |
|     | Initializing           | 3     | The module is currently Initializing, by the [IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)                                                                                                                             |
|     | Initialized            | 4     | The module is initialized and ready to be used.                                                                                                                                                                                                                                     |

## See Also

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>