---
TOCTitle: ModularityException Class
Title: 'ModularityException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModularityException'
ms:mtpsurl: 'modularityexception-class-mspp-modularity.md'
---

# ModularityException Class

Base class for exceptions that are thrown because of a problem with modules.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```c#
[SerializableAttribute]
public class ModularityException : Exception
```
```VB
'Declaration
<SerializableAttribute>
Public Class ModularityException
	Inherits Exception
```

## Inheritance Hierarchy

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;[System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)  
&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.Modularity.ModularityException  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException](/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity)

## See Also

[ModularityException Members](/patterns-practices/reference/modularityexception-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  