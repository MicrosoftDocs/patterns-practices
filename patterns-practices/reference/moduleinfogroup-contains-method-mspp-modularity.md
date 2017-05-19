---
TOCTitle: Contains Method
Title: 'ModuleInfoGroup.Contains Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.Contains(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405906(v=PandP.50)'
---

Prism Class Library

ModuleInfoGroup.Contains Method
===================================

Determines whether the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)) contains a specific value.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

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

     Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50))
	 
     The object to locate in the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)).

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

true if item is found in the [ModuleInfoGroup](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50)); otherwise, false.

### Implements

[ICollection&lt;T&gt;.Contains(T)](http://msdn.microsoft.com/en-us/library/k5cf1d56)

See Also
--------


[ModuleInfoGroup Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup(v=pandp.50))

[ModuleInfoGroup Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfogroup_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
