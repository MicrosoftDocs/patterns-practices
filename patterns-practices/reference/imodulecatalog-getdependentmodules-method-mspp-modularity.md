---
TOCTitle: GetDependentModules Method
Title: 'IModuleCatalog.GetDependentModules Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleCatalog.GetDependentModules(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'imodulecatalog-getdependentmodules-method-mspp-modularity.md'
---

# IModuleCatalog.GetDependentModules Method

Return the list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that *moduleInfo* depends on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)   
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IEnumerable<ModuleInfo> GetDependentModules(
	ModuleInfo moduleInfo
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to get the

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;  
An enumeration of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that *moduleInfo* depends on.

```VB
'Declaration
Function GetDependentModules ( 
	moduleInfo As ModuleInfo
) As IEnumerable(Of ModuleInfo)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to get the

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))  
An enumeration of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that *moduleInfo* depends on.

## See Also

[IModuleCatalog Interface](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)  
[IModuleCatalog Members](/patterns-practices/reference/imodulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  

