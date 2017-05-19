---
TOCTitle: ModuleManager Constructor
Title: 'ModuleManager Constructor (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleManager.\#ctor(Microsoft.Practices.Prism.Modularity.IModuleInitializer,Microsoft.Practices.Prism.Modularity.IModuleCatalog,Microsoft.Practices.Prism.Logging.ILoggerFacade)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405654(v=PandP.50)'
---

Prism Class Library

ModuleManager Constructor
=========================

Initializes an instance of the [ModuleManager](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager) class.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public ModuleManager( IModuleInitializer moduleInitializer, IModuleCatalog moduleCatalog, ILoggerFacade loggerFacade )Public Sub New ( moduleInitializer As IModuleInitializer, moduleCatalog As IModuleCatalog, loggerFacade As ILoggerFacade )
#### Parameters

moduleInitializer  
Type: [Microsoft.Practices.Prism.Modularity.IModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imoduleinitializer)
Service used for initialization of modules.

moduleCatalog  
Type: [Microsoft.Practices.Prism.Modularity.IModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodulecatalog)
Catalog that enumerates the modules to be loaded and initialized.

loggerFacade  
Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade)
Logger used during the load and initialization of modules.

See Also
--------


[ModuleManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulemanager)

[ModuleManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulemanager)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
