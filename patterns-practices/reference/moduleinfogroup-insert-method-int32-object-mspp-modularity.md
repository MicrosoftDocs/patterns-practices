---
TOCTitle: 'Insert Method (Int32, Object)'
Title: 'ModuleInfoGroup.Insert Method (Int32, Object) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Insert(System.Int32,System.Object)'
ms:mtpsurl: 'moduleinfogroup-insert-method-int32-moduleinfo-mspp-modularity.md'
---

# ModuleInfoGroup.Insert Method (Int32, Object)

Inserts an item to the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void Insert(
	int index,
	Object value
)
```

```VB
'Declaration
Public Sub Insert ( 
	index As Integer,
	value As Object
)
```

### Parameters

index  
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index at which value should be inserted.

value  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) to insert into the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). Must be of type [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)

### Implements

[IList.Insert(Int32, Object)](http://msdn.microsoft.com/en-us/library/zkf4388a)

## Exceptions


| Exception                                                                                   | Condition                                                                                                                               |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *index* is not a valid index in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). |
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)       | If value is null.                                                                                                                       |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)           | If value is not of type [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)                      |

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Insert Overload](/patterns-practices/reference/moduleinfogroup-insert-method-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  