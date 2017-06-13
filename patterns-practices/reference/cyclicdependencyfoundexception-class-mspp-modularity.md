---
TOCTitle: CyclicDependencyFoundException Class
Title: 'CyclicDependencyFoundException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException'
ms:mtpsurl: 'cyclicdependencyfoundexception-class-mspp-modularity.md'
---

# CyclicDependencyFoundException Class

Represents the exception that is thrown when there is a circular dependency between modules during the module loading process.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
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

&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;[System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException

## See Also

[CyclicDependencyFoundException Members](/patterns-practices/reference/cyclicdependencyfoundexception-members-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)