---
TOCTitle: 'CreateModule Method (ModuleInfo)'
Title: 'ModuleInitializer.CreateModule Method (ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.CreateModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinitializer-createmodule-method-moduleinfo-mspp-modularity.md'
---

Prism Class Library

ModuleInitializer.CreateModule Method (ModuleInfo)
======================================================

Uses the container to resolve a new [IModule](imodule-interface-mspp-modularity.md) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)


## Syntax


protected virtual IModule CreateModule( ModuleInfo moduleInfo )Protected Overridable Function CreateModule ( moduleInfo As ModuleInfo ) As IModule

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](moduleinfo-class-mspp-modularity.md)

The module to create.

### Return Value

Type: [IModule](imodule-interface-mspp-modularity.md)

A new instance of the module specified by moduleInfo.

See Also
--------


[ModuleInitializer Class](moduleinitializer-class-mspp-modularity.md)

[ModuleInitializer Members](moduleinitializer-members-mspp-modularity.md)

[CreateModule Overload](moduleinitializer-createmodule-method-moduleinfo-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
