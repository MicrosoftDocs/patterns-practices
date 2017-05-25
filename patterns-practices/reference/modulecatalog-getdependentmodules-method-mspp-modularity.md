---
TOCTitle: GetDependentModules Method
Title: 'ModuleCatalog.GetDependentModules Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.GetDependentModules(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.getdependentmodules(v=pandp.50)'
---

Prism Class Library

ModuleCatalog.GetDependentModules Method
============================================

Return the list of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)s that moduleInfo depends on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual IEnumerable&lt;ModuleInfo&gt; GetDependentModules( ModuleInfo moduleInfo )Public Overridable Function GetDependentModules ( moduleInfo As ModuleInfo ) As IEnumerable(Of ModuleInfo)

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
The [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) to get the

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
An enumeration of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) that moduleInfo depends on.
### Implements

[IModuleCatalog.GetDependentModules(ModuleInfo)](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodulecatalog.getdependentmodules(microsoft.practices.prism.modularity.moduleinfo))

Remarks
-------

 If the [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) was not yet validated, this method will call [Validate()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog.validate).

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
