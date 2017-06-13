---
TOCTitle: RemoveAt Method
Title: 'ModuleInfoGroup.RemoveAt Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.RemoveAt(System.Int32)'
ms:mtpsurl: 'moduleinfogroup-removeat-method-mspp-modularity.md'
---

# ModuleInfoGroup.RemoveAt Method

Removes the [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6) item at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RemoveAt(
	int index
)
```

### Parameters

*index*    
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index of the item to remove.

### Implements

[IList&lt;T&gt;.RemoveAt(Int32)](http://msdn.microsoft.com/en-us/library/c93ab5c9)<br/>
[IList.RemoveAt(Int32)](http://msdn.microsoft.com/en-us/library/x5zwtyhy)

## Exceptions


| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *index* is not a valid index in the [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6). |
| [System.NotSupportedException](http://msdn.microsoft.com/en-us/library/8a7a4e64)       | The [IList&lt;T&gt;](http://msdn.microsoft.com/en-us/library/5y536ey6) is read-only.                  |


# ModuleInfoGroup.RemoveAt Method

Removes the [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6) item at the specified index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub RemoveAt ( 
	index As Integer
)
```

### Parameters

*index*    
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index of the item to remove.

### Implements

[IList(Of T).RemoveAt(Int32)](http://msdn.microsoft.com/en-us/library/c93ab5c9)<br/>
[IList.RemoveAt(Int32)](http://msdn.microsoft.com/en-us/library/x5zwtyhy)

## Exceptions


| Exception                                                                                   | Condition                                                                                                             |
|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *index* is not a valid index in the [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6). |
| [System.NotSupportedException](http://msdn.microsoft.com/en-us/library/8a7a4e64)       | The [IList(Of T)](http://msdn.microsoft.com/en-us/library/5y536ey6) is read-only.                  |


## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)<br/>
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>