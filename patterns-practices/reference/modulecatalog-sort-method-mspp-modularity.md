---
TOCTitle: Sort Method
Title: 'ModuleCatalog.Sort Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Sort(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-sort-method-mspp-modularity.md'
---

# ModuleCatalog.Sort Method

Sorts a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity) to return a sorted list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IEnumerable<ModuleInfo> Sort(
	IEnumerable<ModuleInfo> modules
)
```

### Parameters

*modules*   
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)<[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)>   
The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s to sort.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)&gt;  
Sorted list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)



# ModuleCatalog.Sort Method

Sorts a list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s. This method is called by [CompleteListWithDependencies(IEnumerable(of ModuleInfo))](/patterns-practices/reference/modulecatalog-completelistwithdependencies-method-mspp-modularity) to return a sorted list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Protected Overridable Function Sort ( 
	modules As IEnumerable(Of ModuleInfo)
) As IEnumerable(Of ModuleInfo)
```

### Parameters

*modules*   
Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))   
The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s to sort.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity))  
Sorted list of [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)s

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)