---
TOCTitle: CyclicDependencyFoundException Class
Title: 'CyclicDependencyFoundException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException'
ms:mtpsurl: 'cyclicdependencyfoundexception-class-mspp-modularity.md'
---

# CyclicDependencyFoundException Class

Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
[SerializableAttribute]
public class CyclicDependencyFoundException : ModularityException
```
```VB
'Declaration
<SerializableAttribute>
Public Class CyclicDependencyFoundException
	Inherits ModularityException
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
  [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)<br/>
    [Microsoft.Practices.Prism.Modularity.ModularityException](modularityexception-class-mspp-modularity)<br/>
      Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException

## See Also

[CyclicDependencyFoundException Members](cyclicdependencyfoundexception-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace)
