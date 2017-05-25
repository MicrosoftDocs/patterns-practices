---
TOCTitle: FileModuleTypeLoader Class
Title: 'FileModuleTypeLoader Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431477(v=PandP.50)'
---


# FileModuleTypeLoader Class

Loads modules from an arbitrary location on the filesystem. This typeloader is only called if [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50)) classes have a Ref parameter that starts with "file://". This class is only used on the Desktop version of the Prism Library.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class FileModuleTypeLoader : IModuleTypeLoader, 
	IDisposable
```
```VB
'Declaration
Public Class FileModuleTypeLoader
	Implements IModuleTypeLoader, IDisposable
```

## Inheritance Hierarchy

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader

## See Also

[FileModuleTypeLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.filemoduletypeloader_members(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
