---
TOCTitle: Sort Method
Title: 'ModuleCatalog.Sort Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Sort(System.Collections.Generic.IEnumerable{Microsoft.Practices.Prism.Modularity.ModuleInfo})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.sort(v=pandp.50)'
---

Prism Class Library

# ModuleCatalog.Sort Method

Sorts a list of [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))s. This method is called by [CompleteListWithDependencies(IEnumerable&lt;ModuleInfo&gt;)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.completelistwithdependencies(v=pandp.50)) to return a sorted list.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

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

	Type: [System.Collections.Generic.IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)<[ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))>
	The [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))s to sort.

### Return Value
Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))&gt;<br/>
Sorted list of [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))s

## See Also

[ModuleCatalog Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50))

[ModuleCatalog Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
