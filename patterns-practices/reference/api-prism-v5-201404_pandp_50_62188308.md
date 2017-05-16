---
TOCTitle: Solve Method
Title: 'ModuleDependencySolver.Solve Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleDependencySolver.Solve'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405901(v=PandP.50)'
---

Prism Class Library

ModuleDependencySolver..::.Solve Method
=======================================

Calculates an ordered vector according to the defined dependencies. Non-dependant modules appears at the beginning of the resulting array.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public string\[\] Solve()Public Function Solve As String()
#### Return Value

Type: array&lt;[String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)&gt;\[\]()\[\]
The resulting ordered list of modules.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                                                                                                   | Condition                                                                      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity..::.CyclicDependencyFoundException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.cyclicdependencyfoundexception) | This exception is thrown when a cycle is found in the defined depedency graph. |

See Also
--------

<span id="seeAlsoToggle"></span>
[ModuleDependencySolver Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduledependencysolver)

[ModuleDependencySolver Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduledependencysolver)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
