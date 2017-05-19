---
TOCTitle: CyclicDependencyFoundException Class
Title: 'CyclicDependencyFoundException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431474(v=PandP.50)'
---

Prism Class Library

# CyclicDependencyFoundException Class

Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

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

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
  [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)<br/>
    [Microsoft.Practices.Prism.Modularity.ModularityException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modularityexception(v=pandp.50))<br/>
      Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException

## See Also

[CyclicDependencyFoundException Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.cyclicdependencyfoundexception_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
