---
TOCTitle: HandleModuleInitializationError Method
Title: 'ModuleInitializer.HandleModuleInitializationError Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.HandleModuleInitializationError(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.String,System.Exception)'
ms:mtpsurl: 'moduleinitializer-handlemoduleinitializationerror-method-mspp-modularity.md'
---

# ModuleInitializer.HandleModuleInitializationError Method

Handles any exception occurred in the module Initialization process, logs the error using the [ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging) and throws a [ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity). This method can be overridden to provide a different behavior.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual void HandleModuleInitializationError(
	ModuleInfo moduleInfo,
	string assemblyName,
	Exception exception
)
```

```VB
'Declaration
Public Overridable Sub HandleModuleInitializationError ( 
	moduleInfo As ModuleInfo,
	assemblyName As String,
	exception As Exception
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)  
The module metadata where the error happenened.

*assemblyName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The assembly name.

*exception*  
Type: [System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)  
The exception thrown that is the cause of the current error.

## Exceptions


| Exception                                                                                                                                                         | Condition |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Microsoft.Practices.Prism.Modularity.ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity) |           |

## See Also

[ModuleInitializer Class](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)

[ModuleInitializer Members](/patterns-practices/reference/moduleinitializer-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
