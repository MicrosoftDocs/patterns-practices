---
TOCTitle: Contains Method
Title: 'ModuleInfoGroup.Contains Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Contains(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-contains-method-mspp-modularity.md'
---

# ModuleInfoGroup.Contains Method

Determines whether the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) contains a specific value.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool Contains(
	ModuleInfo item
)
```

### Parameters
 
*item*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)   
The object to locate in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
true if *item* is found in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity); otherwise, false.

### Implements

[ICollection&lt;T&gt;.Contains(T)](http://msdn.microsoft.com/en-us/library/k5cf1d56)


## Syntax

```VB
'Declaration
Public Function Contains ( 
	item As ModuleInfo
) As Boolean
```

### Parameters
 
*item*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The object to locate in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
true if *item* is found in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity); otherwise, false.

### Implements

[ICollection(Of T).Contains(T)](http://msdn.microsoft.com/en-us/library/k5cf1d56)

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  