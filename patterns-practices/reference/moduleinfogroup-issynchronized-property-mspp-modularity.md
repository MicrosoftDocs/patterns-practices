---
TOCTitle: IsSynchronized Property
Title: 'ModuleInfoGroup.IsSynchronized Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.IsSynchronized'
ms:mtpsurl: 'moduleinfogroup-issynchronized-property-mspp-modularity.md'
---


# ModuleInfoGroup.IsSynchronized Property

Gets a value indicating whether access to the [ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113) is synchronized (thread safe).


**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)  

## Syntax

```C#
public bool IsSynchronized { get; }
```

```VB
'Declaration
Public ReadOnly Property IsSynchronized As Boolean
	Get
```
### Property Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
true if access to the [ICollection](http://msdn.microsoft.com/en-us/library/b1ht6113) is synchronized (thread safe); otherwise, false.
### Implements

[ICollection.IsSynchronized](http://msdn.microsoft.com/en-us/library/d74ky11w)

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)  
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)