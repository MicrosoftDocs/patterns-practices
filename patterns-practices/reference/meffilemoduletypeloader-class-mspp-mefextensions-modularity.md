---
TOCTitle: MefFileModuleTypeLoader Class
Title: 'MefFileModuleTypeLoader Class (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader'
ms:mtpsurl: 'meffilemoduletypeloader-class-mspp-mefextensions-modularity.md'
---

# MefFileModuleTypeLoader Class

Loads modules from an arbitrary location on the filesystem. This typeloader is only called if [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) classes have a Ref parameter that starts with "file://". This class is only used on the Desktop version of the Prism Library when used with Managed Extensibility Framework.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
public class MefFileModuleTypeLoader : IModuleTypeLoader
```

```VB
'Declaration
Public Class MefFileModuleTypeLoader
	Implements IModuleTypeLoader
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  Microsoft.Practices.Prism.MefExtensions.Modularity.MefFileModuleTypeLoader

## See Also
[MefFileModuleTypeLoader Members](/patterns-practices/reference/meffilemoduletypeloader-members-mspp-mefextensions-modularity)<br/>
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>