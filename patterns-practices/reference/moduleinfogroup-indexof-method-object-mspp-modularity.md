---
TOCTitle: 'IndexOf Method (Object)'
Title: 'ModuleInfoGroup.IndexOf Method (Object) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroup.IndexOf(System.Object)'
ms:mtpsurl: 'moduleinfogroup-indexof-method-moduleinfo-mspp-modularity.md'
---

# ModuleInfoGroup.IndexOf Method (Object)

Determines the index of a specific item in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public int IndexOf(
	Object value
)
```

```VB
'Declaration
Public Function IndexOf ( 
	value As Object
) As Integer
```

### Parameters

*value*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) to locate in the [ModuleInfoGroup](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity). Must be of type [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)

### Return Value

Type: [Int32](http://msdn.microsoft.com/en-us/library/td2s409d)    
The index of value if found in the list; otherwise, -1.

### Implements

[IList.IndexOf(Object)](http://msdn.microsoft.com/en-us/library/2zt6cw37)

## See Also

[ModuleInfoGroup Class](/patterns-practices/reference/moduleinfogroup-class-mspp-modularity)<br/>
[ModuleInfoGroup Members](/patterns-practices/reference/moduleinfogroup-members-mspp-modularity)<br/>
[IndexOf Overload](/patterns-practices/reference/moduleinfogroup-indexof-method-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>