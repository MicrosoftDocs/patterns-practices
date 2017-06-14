---
TOCTitle: MefModuleManager Class
Title: 'MefModuleManager Class (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager'
ms:mtpsurl: 'mefmodulemanager-class-mspp-mefextensions-modularity.md'
---


# MefModuleManager Class

Component responsible for coordinating the modules' type loading and module initialization process.

Component responsible for coordinating the modules' type loading and module initialization process.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
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

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Modularity.ModuleManager](/patterns-practices/reference/modulemanager-class-mspp-modularity)  
Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleManager

## See Also

[MefModuleManager Members](/patterns-practices/reference/mefmodulemanager-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  