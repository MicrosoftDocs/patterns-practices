---
TOCTitle: MefAutoPopulateRegionBehavior Class
Title: 'MefAutoPopulateRegionBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefAutoPopulateRegionBehavior'
ms:mtpsurl: 'mefautopopulateregionbehavior-class-mspp-mefextensions-regions-behaviors.md'
---

# MefAutoPopulateRegionBehavior Class

Exports the AutoPopulateRegionBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public class MefAutoPopulateRegionBehavior : AutoPopulateRegionBehavior
```

```VB
'Declaration
Public Class MefAutoPopulateRegionBehavior
	Inherits AutoPopulateRegionBehavior
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)  
    [Microsoft.Practices.Prism.Regions.Behaviors.AutoPopulateRegionBehavior](/patterns-practices/reference/autopopulateregionbehavior-class-mspp-regions-behaviors)  
      Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefAutoPopulateRegionBehavior

## See Also

[MefAutoPopulateRegionBehavior Members](/patterns-practices/reference/mefautopopulateregionbehavior-members-mspp-mefextensions-regions-behaviors)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)
