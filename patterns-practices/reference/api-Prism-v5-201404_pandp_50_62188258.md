---
TOCTitle: MefModuleManager Constructor
Title: 'MefModuleManager Constructor (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.\#ctor(Microsoft.Practices.Prism.Modularity.IModuleInitializer,Microsoft.Practices.Prism.Modularity.IModuleCatalog,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405582(v=PandP.50)'
---

Prism Class Library

# MefModuleManager Constructor

Initializes a new instance of the [MefModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager(v=pandp.50)) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))


=======
**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll) Version: 5.0.0.0 (5.0.0.0)

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

#### Parameters

*moduleInitializer*

    Type: [Microsoft.Practices.Prism.Modularity.IModuleInitializer](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imoduleinitializer(v=pandp.50))
    Service used for initialization of modules.

*moduleCatalog*

    Type: [Microsoft.Practices.Prism.Modularity.IModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.imodulecatalog(v=pandp.50))
    Catalog that enumerates the modules to be loaded and initialized.

*loggerFacade*

    Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.logging.iloggerfacade(v=pandp.50))
    Logger used during the load and initialization of modules.

## See Also

[MefModuleManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager(v=pandp.50))

[MefModuleManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
