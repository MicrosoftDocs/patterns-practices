---
TOCTitle: GetDependentModulesInner Method
Title: 'ModuleCatalog.GetDependentModulesInner Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.GetDependentModulesInner(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'modulecatalog-getdependentmodulesinner-method-mspp-modularity.md'
---

# ModuleCatalog.GetDependentModulesInner Method

Returns the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) on which the received module dependens on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IEnumerable<ModuleInfo> GetDependentModulesInner(
	ModuleInfo moduleInfo
)
```
### Parameters

*moduleInfo*   
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)   
Module whose dependant modules are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;   
Collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) dependants of *moduleInfo*.

```VB
'Declaration
Protected Overridable Function GetDependentModulesInner ( 
	moduleInfo As ModuleInfo
) As IEnumerable(Of ModuleInfo)
```

### Parameters

*moduleInfo*   
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/mspp-modularity-namespace.moduleinfo)   
Module whose dependant modules are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/mspp-modularity-namespace.moduleinfo))   
Collection of [ModuleInfo](/patterns-practices/reference/mspp-modularity-namespace.moduleinfo) dependants of *moduleInfo*.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/moduleinfo-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/moduleinfo-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>