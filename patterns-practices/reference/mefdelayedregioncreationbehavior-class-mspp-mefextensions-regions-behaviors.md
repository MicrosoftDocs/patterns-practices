---
TOCTitle: MefDelayedRegionCreationBehavior Class
Title: 'MefDelayedRegionCreationBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior(v=pandp.50)'
---

# MefDelayedRegionCreationBehavior Class

Exports the DelayedRegionCreationBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefDelayedRegionCreationBehavior : DelayedRegionCreationBehavior
```

```VB
'Declaration
Public Class MefDelayedRegionCreationBehavior
	Inherits DelayedRegionCreationBehavior
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)</br>
  [Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior(v=pandp.50))</br>
    Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior

## See Also

[MefDelayedRegionCreationBehavior Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors(v=pandp.50))