---
TOCTitle: CopyTo Method
Title: 'ModuleInfoGroup.CopyTo Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.CopyTo(Microsoft.Practices.Prism.Modularity.ModuleInfo[],System.Int32)'
ms:mtpsurl: 'moduleinfogroup-copyto-method-mspp-modularity.md'
---

# ModuleInfoGroup.CopyTo Method

Copies the elements of the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) to an [Array](http://msdn.microsoft.com/en-us/library/czz5hkty), starting at a particular [Array](http://msdn.microsoft.com/en-us/library/czz5hkty) index.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void CopyTo(
	ModuleInfo[] array,
	int arrayIndex
)
```


### Parameters

*array*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)[]  
The one-dimensional [Array](http://msdn.microsoft.com/en-us/library/czz5hkty) that is the destination of the elements copied from [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). The [Array](http://msdn.microsoft.com/en-us/library/czz5hkty) must have zero-based indexing.

*arrayIndex*  
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index in array at which copying begins.

### Implements

[ICollection&lt;T&gt;.CopyTo(T[], Int32)](http://msdn.microsoft.com/en-us/library/0efx51xw)


```VB
'Declaration
Public Sub CopyTo ( 
	array As ModuleInfo(),
	arrayIndex As Integer
)
```

### Parameters

*array*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)()  
The one-dimensional [Array](http://msdn.microsoft.com/en-us/library/czz5hkty) that is the destination of the elements copied from [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). The [Array](http://msdn.microsoft.com/en-us/library/czz5hkty) must have zero-based indexing.

*arrayIndex*    
Type: [System.Int32](http://msdn.microsoft.com/en-us/library/td2s409d)  
The zero-based index in *array* at which copying begins.

### Implements

[ICollection(Of T).CopyTo(T(), Int32)](http://msdn.microsoft.com/en-us/library/0efx51xw)

## Exceptions

| Exception                                                                                   | Condition                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)       | *array* is null.                                                                                                                                                                                                                                                                                                                      |
| [System.ArgumentOutOfRangeException](http://msdn.microsoft.com/en-us/library/8xt94y6e) | *arrayIndex* is less than 0.                                                                                                                                                                                                                                                                                                          |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)           | *array* is multidimensional. -or- *arrayIndex* is equal to or greater than the length of *array*. -or- The number of elements in the source [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity) is greater than the available space from *arrayIndex* to the end of the destination *array*. |


## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  