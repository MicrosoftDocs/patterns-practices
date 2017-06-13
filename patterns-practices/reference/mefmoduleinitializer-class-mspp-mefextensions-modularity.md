---
TOCTitle: MefModuleInitializer Class
Title: 'MefModuleInitializer Class (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer'
ms:mtpsurl: 'mefmoduleinitializer-class-mspp-mefextensions-modularity.md'
---

# MefModuleInitializer Class

Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefModuleInitializer : ModuleInitializer

```

```VB
'Declaration
Public Class MefModuleInitializer
	Inherits ModuleInitializer
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  [Microsoft.Practices.Prism.Modularity.ModuleInitializer](/patterns-practices/reference/moduleinitializer-class-mspp-modularity)

    Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer

## See Also
[MefModuleInitializer Members](/patterns-practices/reference/mefmoduleinitializer-members-mspp-mefextensions-modularity)<br/>
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)<br/>