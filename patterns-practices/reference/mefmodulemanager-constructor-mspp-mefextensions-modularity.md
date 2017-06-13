---
TOCTitle: MefModuleManager Constructor
Title: 'MefModuleManager Constructor (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.\#ctor(Microsoft.Practices.Prism.Modularity.IModuleInitializer,Microsoft.Practices.Prism.Modularity.IModuleCatalog,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'mefmodulemanager-constructor-mspp-mefextensions-modularity.md'
---

# MefModuleManager Constructor

Initializes a new instance of the [MefModuleManager](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public MefModuleManager(
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

[MefModuleManager Class](/patterns-practices/reference/mefmodulemanager-class-mspp-mefextensions-modularity)<br/>
[MefModuleManager Members](/patterns-practices/reference/mefmodulemanager-members-mspp-mefextensions-modularity)<br/>
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>