---
TOCTitle: ModuleNeedsRetrieval Method
Title: 'MefModuleManager.ModuleNeedsRetrieval Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager.ModuleNeedsRetrieval(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405841(v=PandP.50)'
---

Prism Class Library

MefModuleManager.ModuleNeedsRetrieval Method
================================================

Checks if the module needs to be retrieved before it's initialized.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override bool ModuleNeedsRetrieval( ModuleInfo moduleInfo )Protected Overrides Function ModuleNeedsRetrieval ( moduleInfo As ModuleInfo ) As Boolean

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo)
Module that is being checked if needs retrieval.

### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
True if the module needs to be retrieved. Otherwise, false.

See Also
--------


[MefModuleManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[MefModuleManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.mefmodulemanager)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
