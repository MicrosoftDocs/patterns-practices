---
TOCTitle: MefModuleInitializer Class
Title: 'MefModuleInitializer Class (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431449(v=PandP.50)'
---

Prism Class Library

# MefModuleInitializer Class

Exports the ModuleInitializer using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))

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

<span id="remarksToggle"></span> This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

Inheritance Hierarchy

<span id="familyToggle"></span>[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)

  [Microsoft.Practices.Prism.Modularity.ModuleInitializer](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinitializer(v=pandp.50))

    Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer

## See Also


[MefModuleInitializer Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.modularity(v=pandp.50))
