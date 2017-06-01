---
TOCTitle: SolveDependencies Method
Title: 'ModuleCatalog.SolveDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.SolveDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-solvedependencies-method-mspp-modularity.md'
---


# ModuleCatalog.SolveDependencies Method

Checks for cyclic dependencies, by calling the dependencysolver.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected static string[] SolveDependencies(
	IEnumerable<ModuleInfo> modules
)
```
### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;   
the.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]
```VB
'Declaration
Protected Shared Function SolveDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
) As String()
```

### Parameters

modules  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))   
the.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)

[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)

