---
TOCTitle: FileModuleTypeLoader Class
Title: 'FileModuleTypeLoader Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader'
ms:mtpsurl: 'filemoduletypeloader-class-mspp-modularity.md'
---

# FileModuleTypeLoader Class

Loads modules from an arbitrary location on the filesystem. This typeloader is only called if [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes have a Ref parameter that starts with "file://". This class is only used on the Desktop version of the Prism Library.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

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

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Modularity.FileModuleTypeLoader

## See Also
[FileModuleTypeLoader Members](/patterns-practices/reference/filemoduletypeloader-members-mspp-modularity)

[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)
