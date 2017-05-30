---
TOCTitle: MefDelayedRegionCreationBehavior Class
Title: 'MefDelayedRegionCreationBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior'
ms:mtpsurl: 'mefdelayedregioncreationbehavior-class-mspp-mefextensions-regions-behaviors.md'
---

# MefDelayedRegionCreationBehavior Class

Exports the DelayedRegionCreationBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](mspp-mefextensions-regions-behaviors-namespace)

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
  [Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior](delayedregioncreationbehavior-class-mspp-regions-behaviors)</br>
    Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior

## See Also

[MefDelayedRegionCreationBehavior Members](mefdelayedregioncreationbehavior-members-mspp-mefextensions-regions-behaviors)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](mspp-mefextensions-regions-behaviors-namespace)