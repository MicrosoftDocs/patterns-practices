---
TOCTitle: MefModuleManager Constructor
Title: 'MefModuleManager Constructor (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.\#ctor(Microsoft.Practices.Prism.Modularity.IModuleInitializer,Microsoft.Practices.Prism.Modularity.IModuleCatalog,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'mefmodulemanager-constructor-mspp-mefextensions-modularity.md'
---

# MefModuleManager Constructor

Initializes a new instance of the [MefModuleManager](mefmodulemanager-class-mspp-mefextensions-modularity.md) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](mspp-mefextensions-modularity-namespace.md)

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

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

    Type: [Microsoft.Practices.Prism.Modularity.IModuleInitializer](imoduleinitializer-interface-mspp-modularity.md)
    Service used for initialization of modules.

*moduleCatalog*

    Type: [Microsoft.Practices.Prism.Modularity.IModuleCatalog](imodulecatalog-interface-mspp-modularity.md)
    Catalog that enumerates the modules to be loaded and initialized.

*loggerFacade*

    Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](iloggerfacade-interface-mspp-logging.md)
    Logger used during the load and initialization of modules.

## See Also

[MefModuleManager Class](mefmodulemanager-class-mspp-mefextensions-modularity.md)

[MefModuleManager Members](mefmodulemanager-members-mspp-mefextensions-modularity.md)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](mspp-mefextensions-modularity-namespace.md)
