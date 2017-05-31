---
TOCTitle: ValidateDependencies Method
Title: 'ModuleCatalog.ValidateDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.ValidateDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-validatedependencies-method-mspp-modularity.md'
---

# ModuleCatalog.ValidateDependencies Method
Ensures that all the dependencies within modules refer to [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s within that list.
**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax
```c#
protected static void ValidateDependencies(
	IEnumerable<ModuleInfo> modules
)
```
```VB
'Declaration
Protected Shared Sub ValidateDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
)
```
## Parameters

modules 

Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)(Of ([ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))
**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
protected static void ValidateDependencies( IEnumerable&lt;ModuleInfo&gt; modules )Protected Shared Sub ValidateDependencies ( modules As IEnumerable(Of ModuleInfo) )

### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)&gt;)&gt;)

The modules to validate modules for.

## Exceptions
| Exception | Condition |
|--|--|
| [Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity) | Throws if a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) in modules depends on a module that's not in modules. |
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy)                                 | Throws if modules is nullNothingnullptra null reference (Nothing in Visual Basic).                                      |


| Exception                                                                                                                                             | Condition                                                                                                                                                    |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity.ModularityException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modularityexception) | Throws if a [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) in modules depends on a module that's not in modules. |
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)                                                                 | Throws if modules is nullNothingnullptra null reference (Nothing in Visual Basic).                                                                           |
## See Also
[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)

[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
