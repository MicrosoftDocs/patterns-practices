---
TOCTitle: ModularityException Class
Title: 'ModularityException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModularityException'
ms:mtpsurl: 'modularityexception-class-mspp-modularity.md'
---
# ModularityException Class
Base class for exceptions that are thrown because of a problem with modules.
**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

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

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
[SerializableAttribute\] public class ModularityException : Exception&lt;SerializableAttribute&gt; Public Class ModularityException Inherits Exception
  [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)
    Microsoft.Practices.Prism.Modularity.ModularityException
      [Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](/patterns-practices/reference/cyclicdependencyfoundexception-class-mspp-modularity)
      [Microsoft.Practices.Prism.Modularity.DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity)
      [Microsoft.Practices.Prism.Modularity.ModuleInitializeException](/patterns-practices/reference/moduleinitializeexception-class-mspp-modularity)
      [Microsoft.Practices.Prism.Modularity.ModuleNotFoundException](/patterns-practices/reference/modulenotfoundexception-class-mspp-modularity)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException](/patterns-practices/reference/moduletypeloadernotfoundexception-class-mspp-modularity)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](/patterns-practices/reference/moduletypeloadingexception-class-mspp-modularity)

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [System.Exception](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)
    Microsoft.Practices.Prism.Modularity.ModularityException
      [Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.cyclicdependencyfoundexception)
      [Microsoft.Practices.Prism.Modularity.DuplicateModuleException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.duplicatemoduleexception)
      [Microsoft.Practices.Prism.Modularity.ModuleInitializeException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinitializeexception)
      [Microsoft.Practices.Prism.Modularity.ModuleNotFoundException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulenotfoundexception)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduletypeloadernotfoundexception)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduletypeloadingexception)
## See Also
[ModularityException Members](/patterns-practices/reference/modularityexception-members-mspp-modularity)

[ModularityException Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modularityexception)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
