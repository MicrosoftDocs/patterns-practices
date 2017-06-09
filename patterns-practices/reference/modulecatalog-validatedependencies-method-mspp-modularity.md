---
TOCTitle: ValidateDependencies Method
Title: 'ModuleCatalog.ValidateDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.ValidateDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-validatedependencies-method-mspp-modularity.md'
---

# ModuleCatalog.ValidateDependencies Method

Ensures that all the dependencies within *modules* refer to [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s within that list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) 

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected static void ValidateDependencies(
	IEnumerable<ModuleInfo> modules
)
```

### Parameters

*modules*   
Type: [System.Collections.Generic.IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;   
The modules to validate modules for.

## Exceptions

| Exception | Condition |
|--|--|
| [Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity) | Throws if a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) in modules depends on a *module* that's not in *modules*. |
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy)                                 | Throws if *modules* is **null**a null reference (**Nothing** in Visual Basic).|


```VB
'Declaration
Protected Shared Sub ValidateDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
)
```
### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))   
The modules to validate modules for.

## Exceptions

| Exception | Condition|
|----|----|
| [Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity) | Throws if a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) in modules depends on a *module* that's not in *modules*. |
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)                                                                 | Throws if *modules* is **Nothing**a null reference (**Nothing** in Visual Basic).|                                                                           |

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)

[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)