---
TOCTitle: RegionMemberLifetimeBehavior Class
Title: 'RegionMemberLifetimeBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior'
ms:mtpsurl: 'regionmemberlifetimebehavior-class-mspp-regions-behaviors.md'
---


# RegionMemberLifetimeBehavior Class

The RegionMemberLifetimeBehavior determines if items should be removed from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) when they are deactivated.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class RegionMemberLifetimeBehavior : RegionBehavior
```

```VB
'Declaration
Public Class RegionMemberLifetimeBehavior
	Inherits RegionBehavior
```

## Remarks

 The RegionMemberLifetimeBehavior monitors the [ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions) collection to discover items that transition into a deactivated state.

The behavior checks the removed items for either the [IRegionMemberLifetime](/patterns-practices/reference/iregionmemberlifetime-interface-mspp-regions) or the [RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions) (in that order) to determine if it should be kept alive on removal.

If the item in the collection is a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714), it will also check it's DataContext for [IRegionMemberLifetime](/patterns-practices/reference/iregionmemberlifetime-interface-mspp-regions) or the [RegionMemberLifetimeAttribute](/patterns-practices/reference/regionmemberlifetimeattribute-class-mspp-regions).

The order of checks are:
1.  Region Item's IRegionMemberLifetime.KeepAlive value.
2.  Region Item's DataContext's IRegionMemberLifetime.KeepAlive value.
3.  Region Item's RegionMemberLifetimeAttribute.KeepAlive value.
4.  Region Item's DataContext's RegionMemberLifetimeAttribute.KeepAlive value.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
    Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior  
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior](/patterns-practices/reference/mefregionmemberlifetimebehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[RegionMemberLifetimeBehavior Members](/patterns-practices/reference/regionmemberlifetimebehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
