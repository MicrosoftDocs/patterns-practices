---
TOCTitle: Contains Method
Title: 'ModuleInfoGroup.Contains Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Contains(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'moduleinfogroup-contains-method-mspp-modularity.md'
---

Prism Class Library

ModuleInfoGroup.Contains Method
===================================

Determines whether the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md) contains a specific value.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)


## Syntax


```C#
public bool Contains(
	ModuleInfo item
)
```
```VB
'Declaration
Public Function Contains ( 
	item As ModuleInfo
) As Boolean
```

*item*  

     Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](moduleinfo-class-mspp-modularity.md)
	 
     The object to locate in the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if item is found in the [ModuleInfoGroup](moduleinfogroup-class-mspp-modularity.md); otherwise, false.

### Implements

[ICollection&lt;T&gt;.Contains(T)](http://msdn.microsoft.com/en-us/library/k5cf1d56)

See Also
--------


[ModuleInfoGroup Class](moduleinfogroup-class-mspp-modularity.md)

[ModuleInfoGroup Members](moduleinfogroup-members-mspp-modularity.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
