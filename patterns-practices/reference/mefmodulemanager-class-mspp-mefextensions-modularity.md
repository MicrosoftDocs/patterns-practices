---
TOCTitle: MefModuleManager Class
Title: 'MefModuleManager Class (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431450(v=PandP.50)'
---


# MefModuleManager Class

Component responsible for coordinating the modules' type loading and module initialization process.

Component responsible for coordinating the modules' type loading and module initialization process.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefModuleManager : ModuleManager, 
	IPartImportsSatisfiedNotification
```

```VB
'Declaration
Public Class MefModuleManager
	Inherits ModuleManager
	Implements IPartImportsSatisfiedNotification
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  [Microsoft.Practices.Prism.Modularity.ModuleManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulemanager(v=pandp.50))
  
    Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager

## See Also

[MefModuleManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmodulemanager_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
