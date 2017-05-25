---
TOCTitle: CompleteListWithDependencies Method
Title: 'IModuleCatalog.CompleteListWithDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.IModuleCatalog.CompleteListWithDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'imodulecatalog-completelistwithdependencies-method-mspp-modularity.md'
---

# IModuleCatalog.CompleteListWithDependencies Method

Returns the collection of [ModuleInfo](moduleinfo-class-mspp-modularity.md)s that contain both the [ModuleInfo](moduleinfo-class-mspp-modularity.md)s in modules, but also all the modules they depend on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

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

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](moduleinfo-class-mspp-modularity.md)&gt;

The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](moduleinfo-class-mspp-modularity.md)&gt;

A collection of [ModuleInfo](moduleinfo-class-mspp-modularity.md) that contains both all [ModuleInfo](moduleinfo-class-mspp-modularity.md)s in modules and also all the [ModuleInfo](moduleinfo-class-mspp-modularity.md) they depend on.

```VB
'Declaration
Function CompleteListWithDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
) As IEnumerable(Of ModuleInfo)
)
```


### Parameters

*modules* 

Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](moduleinfo-class-mspp-modularity.md))

The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](moduleinfo-class-mspp-modularity.md))

A collection of [ModuleInfo](moduleinfo-class-mspp-modularity.md) that contains both all [ModuleInfo](moduleinfo-class-mspp-modularity.md)s in modules and also all the [ModuleInfo](moduleinfo-class-mspp-modularity.md) they depend on.

## See Also

[IModuleCatalog Interface](imodulecatalog-interface-mspp-modularity.md)

[IModuleCatalog Members](imodulecatalog-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
