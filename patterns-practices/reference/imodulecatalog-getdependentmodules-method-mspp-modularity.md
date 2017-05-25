---
TOCTitle: GetDependentModules Method
Title: 'IModuleCatalog.GetDependentModules Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleCatalog.GetDependentModules(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'imodulecatalog-getdependentmodules-method-mspp-modularity.md'
---

Prism Class Library

IModuleCatalog.GetDependentModules Method
=============================================

Return the list of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)s that moduleInfo depends on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


IEnumerable&lt;ModuleInfo&gt; GetDependentModules( ModuleInfo moduleInfo )Function GetDependentModules ( moduleInfo As ModuleInfo ) As IEnumerable(Of ModuleInfo)

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
The [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) to get the

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
An enumeration of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) that moduleInfo depends on.

See Also
--------


[IModuleCatalog Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog)

[IModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.imodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
