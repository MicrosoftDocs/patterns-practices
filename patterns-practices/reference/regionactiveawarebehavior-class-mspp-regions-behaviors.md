---
TOCTitle: RegionActiveAwareBehavior Class
Title: 'RegionActiveAwareBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionActiveAwareBehavior'
ms:mtpsurl: 'regionactiveawarebehavior-class-mspp-regions-behaviors.md'
---

# RegionActiveAwareBehavior Class

Behavior that monitors a [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) object and changes the value for the [IsActive](https://msdn.microsoft.com/library/microsoft.practices.prism.iactiveaware.isactive) property when an object that implements [IActiveAware](https://msdn.microsoft.com/library/microsoft.practices.prism.iactiveaware) gets added or removed from the collection.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public class RegionActiveAwareBehavior : IRegionBehaviorPublic Class RegionActiveAwareBehavior Implements IRegionBehavior

## Remarks

 This class can also sync the active state for any scoped regions directly on the view based on the [SyncActiveStateAttribute](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.syncactivestateattribute). If you use the [Add(Object, String, Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.add(system.object%2csystem.string%2csystem.boolean)) method with the createRegionManagerScope option, the scoped manager will be attached to the view.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Regions.Behaviors.RegionActiveAwareBehavior
    [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionActiveAwareBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionactiveawarebehavior)

## See Also
[RegionActiveAwareBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.regionactiveawarebehavior)<br/>
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)<br/>