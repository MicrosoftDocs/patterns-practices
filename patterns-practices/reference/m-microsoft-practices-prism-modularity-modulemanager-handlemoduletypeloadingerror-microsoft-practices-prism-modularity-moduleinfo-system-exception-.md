---
TOCTitle: HandleModuleTypeLoadingError Method
Title: 'ModuleManager.HandleModuleTypeLoadingError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.HandleModuleTypeLoadingError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.Exception)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405927(v=PandP.50)'
---

Prism Class Library

ModuleManager..::.HandleModuleTypeLoadingError Method
=====================================================

Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) and throws a [ModuleTypeLoadingException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduletypeloadingexception). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual void HandleModuleTypeLoadingError( ModuleInfo moduleInfo, Exception exception )Protected Overridable Sub HandleModuleTypeLoadingError ( moduleInfo As ModuleInfo, exception As Exception )
#### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity..::.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The module metadata where the error happenened.

<!-- -->

exception  
Type: [System..::.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)
The exception thrown that is the cause of the current error.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                                                                                           | Condition |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity..::.ModuleTypeLoadingException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduletypeloadingexception) |           |

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager)

[ModuleManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
