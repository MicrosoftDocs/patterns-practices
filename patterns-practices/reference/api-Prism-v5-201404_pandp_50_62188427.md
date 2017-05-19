---
TOCTitle: HandleModuleTypeLoadingError Method
Title: 'ModuleManager.HandleModuleTypeLoadingError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.HandleModuleTypeLoadingError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.Exception)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405927(v=PandP.50)'
---

# ModuleManager.HandleModuleTypeLoadingError Method 

Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.logging.iloggerfacade(v=pandp.50)) and throws a [ModuleTypeLoadingException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadingexception(v=pandp.50)). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual void HandleModuleTypeLoadingError(
	ModuleInfo moduleInfo,
	Exception exception
)
```

## Syntax

```VB
'Declaration
Protected Overridable Sub HandleModuleTypeLoadingError ( 
	moduleInfo As ModuleInfo,
	exception As Exception
)
```

#### Parameters

*moduleInfo*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The module metadata where the error happenened.

*exception*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The exception thrown that is the cause of the current error.

## Exceptions


<span id="exceptionsToggle"></span>
| Exception                                                                                                                                                           | Condition |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadingexception(v=pandp.50)) |           |

## See Also

[ModuleManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50))

[ModuleManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
