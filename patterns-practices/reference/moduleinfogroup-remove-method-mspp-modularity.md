---
TOCTitle: Remove Method
Title: 'ModuleInfoGroup.Remove Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Remove(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-remove-method-mspp-modularity.md'
---


# ModuleInfoGroup.Remove Method

Removes the first occurrence of a specific object from the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool Remove( ModuleInfo item )
```

### Parameters

*item*

Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)

The object to remove from the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if *item* was successfully removed from the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity); otherwise, false. This method also returns false if item is not found in the original [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Implements

[ICollection&lt;T&gt;.Remove(T)](http://msdn.microsoft.com/en-us/library/bye7h94w)

## Syntax

```VB
'Declaration
Public Function Remove ( item As ModuleInfo ) As Boolean
```

### Parameters

*item*

Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)

The object to remove from the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if *item* was successfully removed from the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity); otherwise, false. This method also returns false if item is not found in the original [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Implements

[ICollection(Of T).Remove(T)](http://msdn.microsoft.com/en-us/library/bye7h94w)


## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)

[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
