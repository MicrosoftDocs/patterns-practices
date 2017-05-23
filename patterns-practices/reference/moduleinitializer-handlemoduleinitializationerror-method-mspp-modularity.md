---
TOCTitle: HandleModuleInitializationError Method
Title: 'ModuleInitializer.HandleModuleInitializationError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.HandleModuleInitializationError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.String,System.Exception)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405923(v=PandP.50)'
---

Prism Class Library

ModuleInitializer.HandleModuleInitializationError Method
============================================================

Handles any exception occurred in the module Initialization process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade) and throws a [ModuleInitializeException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializeexception). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual void HandleModuleInitializationError( ModuleInfo moduleInfo, string assemblyName, Exception exception )Public Overridable Sub HandleModuleInitializationError ( moduleInfo As ModuleInfo, assemblyName As String, exception As Exception )

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The module metadata where the error happenened.

assemblyName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The assembly name.

exception  
Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)
The exception thrown that is the cause of the current error.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                                                                                         | Condition |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity.ModuleInitializeException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializeexception) |           |

See Also
--------


[ModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinitializer)

[ModuleInitializer Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinitializer)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
