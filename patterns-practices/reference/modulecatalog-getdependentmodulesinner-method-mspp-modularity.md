---
TOCTitle: GetDependentModulesInner Method
Title: 'ModuleCatalog.GetDependentModulesInner Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.GetDependentModulesInner(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405878(v=PandP.50)'
---


# ModuleCatalog.GetDependentModulesInner Method

Returns the [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) on which the received module dependens on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

protected virtual IEnumerable&lt;ModuleInfo&gt; GetDependentModulesInner( ModuleInfo moduleInfo )Protected Overridable Function GetDependentModulesInner ( moduleInfo As ModuleInfo ) As IEnumerable(Of ModuleInfo)

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
Module whose dependant modules are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)
Collection of [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) dependants of moduleInfo.

## See Also

[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
