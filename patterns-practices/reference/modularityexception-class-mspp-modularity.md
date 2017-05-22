---
TOCTitle: ModularityException Class
Title: 'ModularityException Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModularityException'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431488(v=PandP.50)'
---


# ModularityException Class


Base class for exceptions that are thrown because of a problem with modules.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50).aspx)

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

  [System.Exception](http://msdn2.microsoft.com/en-us/library/c18k6c59)

    Microsoft.Practices.Prism.Modularity.ModularityException
      [Microsoft.Practices.Prism.Modularity.CyclicDependencyFoundException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.cyclicdependencyfoundexception(v=pandp.50).aspx)
      [Microsoft.Practices.Prism.Modularity.DuplicateModuleException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.duplicatemoduleexception(v=pandp.50).aspx)
      [Microsoft.Practices.Prism.Modularity.ModuleInitializeException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinitializeexception(v=pandp.50).aspx)
      [Microsoft.Practices.Prism.Modularity.ModuleNotFoundException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulenotfoundexception(v=pandp.50).aspx)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoaderNotFoundException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadernotfoundexception(v=pandp.50).aspx)
      [Microsoft.Practices.Prism.Modularity.ModuleTypeLoadingException](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduletypeloadingexception(v=pandp.50).aspx)

## See Also

[ModularityException Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modularityexception_members(v=pandp.50).aspx)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50).aspx)
