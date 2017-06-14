---
TOCTitle: 'CreateModule Method (ModuleInfo)'
Title: 'MefModuleInitializer.CreateModule Method (ModuleInfo) (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer.CreateModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'mefmoduleinitializer-createmodule-method-moduleinfo-mspp-mefextensions-modularity.md'
---

# MefModuleInitializer.CreateModule Method (ModuleInfo)

Uses the container to resolve a new [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override IModule CreateModule(
	ModuleInfo moduleInfo
)
```
```VB
'Declaration
Protected Overrides Function CreateModule ( 
	moduleInfo As ModuleInfo
) As IModule
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module to create.

### Return Value

Type: [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity)  
A new instance of the module specified by *moduleInfo*.

## See Also

[MefModuleInitializer Class](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)  
[MefModuleInitializer Members](/patterns-practices/reference/mefmoduleinitializer-members-mspp-mefextensions-modularity)  
[CreateModule Overload](/patterns-practices/reference/mefmoduleinitializer-createmodule-method-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  