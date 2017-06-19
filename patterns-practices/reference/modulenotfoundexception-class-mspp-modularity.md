---
TOCTitle: ModuleNotFoundException Class
Title: 'ModuleNotFoundException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleNotFoundException'
ms:mtpsurl: 'modulenotfoundexception-class-mspp-modularity.md'
---


# ModuleNotFoundException Class

Exception thrown when a requested [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) is not found.

Exception thrown when a requested [OnDemand](/patterns-practices/reference/initializationmode-enumeration-mspp-modularity)[IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) was not found.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
[SerializableAttribute]
public class ModuleNotFoundException : ModularityException
```
```VB
'Declaration
<SerializableAttribute>
Public Class ModuleNotFoundException
	Inherits ModularityException
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [System.Exception](http://msdn.microsoft.com/en-us/library/c18k6c59)  
    [Microsoft-Practices-Prism-Modularity-ModularityException](/patterns-practices/reference/modularityexception-class-mspp-modularity)  
      Microsoft.Practices.Prism.Modularity.ModuleNotFoundException

## See Also

[ModuleNotFoundException Members](/patterns-practices/reference/modulenotfoundexception-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  