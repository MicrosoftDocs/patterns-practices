---
TOCTitle: HandleModuleTypeLoadingError Method
Title: 'ModuleManager.HandleModuleTypeLoadingError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.HandleModuleTypeLoadingError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.Exception)'
ms:mtpsurl: 'modulemanager-handlemoduletypeloadingerror-method-mspp-modularity.md'
---

# ModuleManager.HandleModuleTypeLoadingError Method 

Handles any exception occurred in the module typeloading process, logs the error using the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual void HandleModuleTypeLoadingError(
	ModuleInfo moduleInfo,
	Exception exception
)
```

```VB
'Declaration
Protected Overridable Sub HandleModuleTypeLoadingError ( 
	moduleInfo As ModuleInfo,
	exception As Exception
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module metadata where the error happenened.

*exception*  
Type: [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)  
The exception thrown that is the cause of the current error.

## Exceptions


| Exception                                                                                                                                                           | Condition |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity) |           |

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)

[ModuleManager Members](/patterns-practices/reference/modulemanager-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
