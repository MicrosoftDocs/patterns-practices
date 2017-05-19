---
TOCTitle: 'CreateModule Method (ModuleInfo)'
Title: 'MefModuleInitializer.CreateModule Method (ModuleInfo) (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer.CreateModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405840(v=PandP.50)'
---

Prism Class Library

MefModuleInitializer.CreateModule Method (ModuleInfo)
=========================================================

Uses the container to resolve a new [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule) by specifying its [Type](http://msdn2.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override IModule CreateModule( ModuleInfo moduleInfo )Protected Overrides Function CreateModule ( moduleInfo As ModuleInfo ) As IModule

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
The module to create.

### Return Value

Type: [IModule](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.imodule)
A new instance of the module specified by moduleInfo.

See Also
--------


[MefModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[MefModuleInitializer Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[CreateModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer.createmodule)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
