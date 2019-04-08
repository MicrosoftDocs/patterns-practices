---
TOCTitle: CompleteListWithDependencies Method
Title: 'IModuleCatalog.CompleteListWithDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleCatalog.CompleteListWithDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'imodulecatalog-completelistwithdependencies-method-mspp-modularity.md'
---

# IModuleCatalog.CompleteListWithDependencies Method

Returns the collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that contain both the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in *modules*, but also all the modules they depend on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IEnumerable<ModuleInfo> CompleteListWithDependencies(
	IEnumerable<ModuleInfo> modules
)
```

### Parameters

*modules*  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;  
The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;  
A collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that contains both all [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in *modules* and also all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) they depend on.


```VB
'Declaration
Function CompleteListWithDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
) As IEnumerable(Of ModuleInfo)
)
```

### Parameters

*modules*  
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))  
The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))  
A collection of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that contains both all [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in *modules* and also all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) they depend on.

## See Also

[IModuleCatalog Interface](/patterns-practices/reference/imodulecatalog-interface-mspp-modularity)  
[IModuleCatalog Members](/patterns-practices/reference/imodulecatalog-members-mspp-modularity)   
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  