---
TOCTitle: 'CreateModule Method (ModuleInfo)'
Title: 'ModuleInitializer.CreateModule Method (ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInitializer.CreateModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinitializer-createmodule-method-moduleinfo-mspp-modularity.md'
---

# ModuleInitializer.CreateModule Method (ModuleInfo)

Uses the container to resolve a new [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) by specifying its [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IModule CreateModule(
	ModuleInfo moduleInfo
)
```
```VB
'Declaration
Protected Overridable Function CreateModule ( 
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

[ModuleInitializer Class](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)  
[ModuleInitializer Members](/patterns-practices/reference/moduleinitializer-members-mspp-modularity)  
[CreateModule Overload](/patterns-practices/reference/moduleinitializer-createmodule-method-moduleinfo-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  