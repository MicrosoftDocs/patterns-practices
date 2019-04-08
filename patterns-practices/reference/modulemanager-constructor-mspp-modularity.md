---
TOCTitle: ModuleManager Constructor
Title: 'ModuleManager Constructor (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.\#ctor(Microsoft.Practices.Prism.Modularity.IModuleInitializer,Microsoft.Practices.Prism.Modularity.IModuleCatalog,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'modulemanager-constructor-mspp-modularity.md'
---

# ModuleManager Constructor

Initializes an instance of the [ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity) class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleManager(
	IModuleInitializer moduleInitializer,
	IModuleCatalog moduleCatalog,
	ILoggerFacade loggerFacade
)
```

```VB
'Declaration
Public Sub New ( 
	moduleInitializer As IModuleInitializer,
	moduleCatalog As IModuleCatalog,
	loggerFacade As ILoggerFacade
)
```

### Parameters

*moduleInitializer*  
Type: [Microsoft.Practices.Prism.Modularity.IModuleInitializer](/patterns-practices/reference/imoduleinitializer-interface-mspp-modularity)  
Service used for initialization of modules.

*moduleCatalog*  
Type: [Microsoft.Practices.Prism.Modularity.IModuleCatalog](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)  
Catalog that enumerates the modules to be loaded and initialized.

*loggerFacade*  
Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)  
Logger used during the load and initialization of modules.

## See Also

[ModuleManager Class](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
[ModuleManager Members](/patterns-practices/reference/modulemanager-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  