---
TOCTitle: ClearChildViewsRegionBehavior Class
Title: 'ClearChildViewsRegionBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.ClearChildViewsRegionBehavior'
ms:mtpsurl: 'clearchildviewsregionbehavior-class-mspp-regions-behaviors.md'
---

# ClearChildViewsRegionBehavior Class

Behavior that removes the RegionManager attached property of all the views in a region once the RegionManager property of a region becomes null. This is useful when removing views with nested regions, to ensure these nested regions get removed from the RegionManager as well.

### Remarks

This behavior does not apply by default. In order to activate it, the ClearChildViews attached property must be set to True in the view containing the affected child regions.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class ClearChildViewsRegionBehavior : RegionBehavior
```

```VB
'Declaration
Public Class ClearChildViewsRegionBehavior
	Inherits RegionBehavior
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)
    Microsoft.Practices.Prism.Regions.Behaviors.ClearChildViewsRegionBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefClearChildViewsRegionBehavior](/patterns-practices/reference/mefclearchildviewsregionbehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[ClearChildViewsRegionBehavior Members](/patterns-practices/reference/clearchildviewsregionbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  