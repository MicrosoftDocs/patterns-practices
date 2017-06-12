---
TOCTitle: Solve Method
Title: 'ModuleDependencySolver.Solve Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDependencySolver.Solve'
ms:mtpsurl: 'moduledependencysolver-solve-method-mspp-modularity.md'
---

# ModuleDependencySolver.Solve Method

Calculates an ordered vector according to the defined dependencies. Non-dependant modules appears at the beginning of the resulting array.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public string[] Solve()
```

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]

The resulting ordered list of modules.

## Syntax

```VB
'Declaration
Public Function Solve As String()
```

### Return Value

Return Value
Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()

The resulting ordered list of modules.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)</td>
<td>This exception is thrown when a cycle is found in the defined depedency graph.</td>
</tr>
</tbody>
</table>

## See Also

[ModuleDependencySolver Class](/patterns-practices/reference/moduledependencysolver-class-mspp-modularity)

[ModuleDependencySolver Members](/patterns-practices/reference/moduledependencysolver-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)