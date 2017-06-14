---
TOCTitle: ModuleInitializer Constructor
Title: 'ModuleInitializer Constructor (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.\#ctor(Microsoft.Practices.ServiceLocation.IServiceLocator,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'moduleinitializer-constructor-mspp-modularity.md'
---

# ModuleInitializer Constructor

Initializes a new instance of [ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public ModuleInitializer(
	IServiceLocator serviceLocator,
	ILoggerFacade loggerFacade
)
```

```VB
'Declaration
Public Sub New ( 
	serviceLocator As IServiceLocator,
	loggerFacade As ILoggerFacade
)
```

### Parameters

*serviceLocator*  
Type: IServiceLocator  
The container that will be used to resolve the modules by specifying its type.

*loggerFacade*  
Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)  
The logger to use.

## See Also

[ModuleInitializer Class](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)  
[ModuleInitializer Members](/patterns-practices/reference/moduleinitializer-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  