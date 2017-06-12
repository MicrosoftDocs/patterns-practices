---
TOCTitle: MefRegionActiveAwareBehavior Class
Title: 'MefRegionActiveAwareBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionActiveAwareBehavior'
ms:mtpsurl: 'mefregionactiveawarebehavior-class-mspp-mefextensions-regions-behaviors.md'
---

# MefRegionActiveAwareBehavior Class

Exports the RegionActiveAwareBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionActiveAwareBehavior : RegionActiveAwareBehavior
```

```VB
'Declaration
Public Class MefRegionActiveAwareBehavior
	Inherits RegionActiveAwareBehavior
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
  [Microsoft.Practices.Prism.Regions.Behaviors.RegionActiveAwareBehavior](/patterns-practices/reference/regionactiveawarebehavior-class-mspp-regions-behaviors)
    Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionActiveAwareBehavior

## See Also

[MefRegionActiveAwareBehavior Members](/patterns-practices/reference/mefregionactiveawarebehavior-members-mspp-mefextensions-regions-behaviors)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)