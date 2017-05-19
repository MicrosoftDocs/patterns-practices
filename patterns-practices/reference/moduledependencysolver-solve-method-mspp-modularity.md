---
TOCTitle: Solve Method
Title: 'ModuleDependencySolver.Solve Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDependencySolver.Solve'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405901(v=PandP.50)'
---

# ModuleDependencySolver.Solve Method

Calculates an ordered vector according to the defined dependencies. Non-dependant modules appears at the beginning of the resulting array.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public string[] Solve()
```

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]</br>
The resulting ordered list of modules.

## Syntax

```VB
'Declaration
Public Function Solve As String()
```

Return Value
Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()</br>
The resulting ordered list of modules.

## Exceptions
----------

|Exception | Condition |
|[Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.cyclicdependencyfoundexception(v=pandp.50)) | This exception is thrown when a cycle is found in the defined depedency graph. |

## See Also

[ModuleDependencySolver Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencysolver(v=pandp.50))

[ModuleDependencySolver Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduledependencysolver_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))