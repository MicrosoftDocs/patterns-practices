---
TOCTitle: 'Insert Method (Int32, ModuleInfo)'
Title: 'ModuleInfoGroup.Insert Method (Int32, ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Insert(System.Int32,Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-insert-method-int32-moduleinfo-mspp-modularity.md'
---

# ModuleInfoGroup.Insert Method (Int32, ModuleInfo)

Inserts an item to the [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6) at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void Insert(
	int index,
	ModuleInfo item
)
```

### Parameters

*index*    
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index at which *item* should be inserted.

*item*    
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The object to insert into the [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6).

### Implements

[IList&lt;T&gt;.Insert(Int32, T)](http://msdn.microsoft.com/en-us/library/8zsfbxz8)

## Exceptions


| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *index* is not a valid index in the [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6). |


# ModuleInfoGroup.Insert Method (Int32, ModuleInfo)

Inserts an item to the [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6) at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub Insert ( 
	index As Integer,
	item As ModuleInfo
)
```

### Parameters

*index*  
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)<br/>
The zero-based *index* at which item should be inserted.

*item*    
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The object to insert into the [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6).

### Implements

[IList(Of T).Insert(Int32, T)](http://msdn.microsoft.com/en-us/library/8zsfbxz8)

## Exceptions


| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *index* is not a valid index in the [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6). |




## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)

[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)

[Insert Overload](/patterns-practices/reference/moduleinfogroup-insert-method-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
