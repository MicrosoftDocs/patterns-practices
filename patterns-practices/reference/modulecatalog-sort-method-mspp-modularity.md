---
TOCTitle: Sort Method
Title: 'ModuleCatalog.Sort Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Sort(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'modulecatalog-sort-method-mspp-modularity.md'
---

# ModuleCatalog.Sort Method

Sorts a list of [ModuleInfo](moduleinfo-class-mspp-modularity.md)s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](modulecatalog-completelistwithdependencies-method-mspp-modularity.md) to return a sorted list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual IEnumerable<ModuleInfo> Sort(
	IEnumerable<ModuleInfo> modules
)
```

```VB
'Declaration
Protected Overridable Function Sort ( 
	modules As IEnumerable(Of ModuleInfo)
) As IEnumerable(Of ModuleInfo)
```
### Parameters

*modules*

	Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)<[ModuleInfo](moduleinfo-class-mspp-modularity.md)>
	The [ModuleInfo](moduleinfo-class-mspp-modularity.md)s to sort.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](moduleinfo-class-mspp-modularity.md)&gt;<br/>
Sorted list of [ModuleInfo](moduleinfo-class-mspp-modularity.md)s

## See Also

[ModuleCatalog Class](modulecatalog-class-mspp-modularity.md)

[ModuleCatalog Members](modulecatalog-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
