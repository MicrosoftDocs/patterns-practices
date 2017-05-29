---
TOCTitle: HandleModuleTypeLoadingError Method
Title: 'ModuleManager.HandleModuleTypeLoadingError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.HandleModuleTypeLoadingError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.Exception)'
ms:mtpsurl: 'modulemanager-handlemoduletypeloadingerror-method-mspp-modularity.md'
---

# ModuleManager.HandleModuleTypeLoadingError Method 

Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](iloggerfacade-interface-mspp-logging.md) and throws a [ModuleTypeLoadingException](moduletypeloadingexception-class-mspp-modularity.md). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

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
### Parameters

*moduleInfo*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](moduleinfo-class-mspp-modularity.md)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The module metadata where the error happenened.

*exception*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The exception thrown that is the cause of the current error.

## Exceptions

<span id="exceptionsToggle"></span>
| Exception                                                                                                                                                           | Condition |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](moduletypeloadingexception-class-mspp-modularity.md) |           |

## See Also

[ModuleManager Class](modulemanager-class-mspp-modularity.md)

[ModuleManager Members](modulemanager-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
