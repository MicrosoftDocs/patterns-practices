---
TOCTitle: Remove Method
Title: 'ModuleInfoGroup.Remove Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Remove(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-remove-method-mspp-modularity.md'
---

# ModuleInfoGroup.Remove Method

Removes the first occurrence of a specific object from the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md).

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
public bool Remove( ModuleInfo item )
```
```VB
'Declaration
Public Function Remove ( item As ModuleInfo ) As Boolean
```
### Parameters

*item*  
	Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](moduleinfo-class-mspp-modularity.md)
	The object to remove from the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if item was successfully removed from the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md); otherwise, false. This method also returns false if item is not found in the original [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md).
### Implements

[ICollection&lt;T&gt;.Remove(T)](http://msdn.microsoft.com/en-us/library/bye7h94w)

## See Also
[ModuleInfoGroup Class](moduleinfogroup-class-mspp-modularity.md)

[ModuleInfoGroup Members](moduleinfogroup-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
