---
TOCTitle: CompleteListWithDependencies Method
Title: 'ModuleCatalog.CompleteListWithDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.CompleteListWithDependencies(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-completelistwithdependencies-method-mspp-modularity.md'
---

# ModuleCatalog.CompleteListWithDependencies Method

Returns a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s that contain both the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in *modules*, but also all the modules they depend on.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public virtual IEnumerable<ModuleInfo> CompleteListWithDependencies(
	IEnumerable<ModuleInfo> modules
)
```
### Parameters

*modules*   
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;   
The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;   
A list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that contains both all [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in modules but also all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) they depend on.

### Implements

[IModuleCatalog.CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](/patterns-practices/reference/imodulecatalog-completelistwithdependencies-method-mspp-modularity)

```VB
'Declaration
Public Overridable Function CompleteListWithDependencies ( 
	modules As IEnumerable(Of ModuleInfo)
) As IEnumerable(Of ModuleInfo)
```

### Parameters

*modules*   
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))   
The modules to get the dependencies for.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))   
A list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) that contains both all [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s in modules but also all the [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) they depend on.
### Implements

[IModuleCatalog.CompleteListWithDependencies(IEnumerable(Of ModuleInfo))](/patterns-practices/reference/imodulecatalog-completelistwithdependencies-method-mspp-modularity)

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>