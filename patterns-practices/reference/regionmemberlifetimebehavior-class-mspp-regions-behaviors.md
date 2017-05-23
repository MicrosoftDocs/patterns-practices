---
TOCTitle: RegionMemberLifetimeBehavior Class
Title: 'RegionMemberLifetimeBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431518(v=PandP.50)'
---

Prism Class Library

RegionMemberLifetimeBehavior Class
==================================

The RegionMemberLifetimeBehavior determines if items should be removed from the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) when they are deactivated.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class RegionMemberLifetimeBehavior : RegionBehaviorPublic Class RegionMemberLifetimeBehavior Inherits RegionBehavior

Remarks
-------

<span id="remarksToggle"></span> The RegionMemberLifetimeBehavior monitors the [ActiveViews](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activeviews) collection to discover items that transition into a deactivated state.

The behavior checks the removed items for either the [IRegionMemberLifetime](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmemberlifetime) or the [RegionMemberLifetimeAttribute](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmemberlifetimeattribute) (in that order) to determine if it should be kept alive on removal.

If the item in the collection is a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714), it will also check it's DataContext for [IRegionMemberLifetime](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmemberlifetime) or the [RegionMemberLifetimeAttribute](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmemberlifetimeattribute).

The order of checks are:
1.  Region Item's IRegionMemberLifetime.KeepAlive value.
2.  Region Item's DataContext's IRegionMemberLifetime.KeepAlive value.
3.  Region Item's RegionMemberLifetimeAttribute.KeepAlive value.
4.  Region Item's DataContext's RegionMemberLifetimeAttribute.KeepAlive value.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions.RegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior)
    Microsoft.Practices.Prism.Regions.Behaviors.RegionMemberLifetimeBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionMemberLifetimeBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmemberlifetimebehavior)

See Also
--------


[RegionMemberLifetimeBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.regionmemberlifetimebehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
