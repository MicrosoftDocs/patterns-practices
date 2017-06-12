---
TOCTitle: RegionManagerAccessor Property
Title: 'DelayedRegionCreationBehavior.RegionManagerAccessor Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.RegionManagerAccessor'
ms:mtpsurl: 'delayedregioncreationbehavior-regionmanageraccessor-property-mspp-regions-behaviors.md'
---

# DelayedRegionCreationBehavior.RegionManagerAccessor Property

Sets a class that interfaces between the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) 's static properties/events and this behavior, so this behavior can be tested in isolation.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IRegionManagerAccessor RegionManagerAccessor { get; set; }
```

```VB
'Declaration
Public Property RegionManagerAccessor As IRegionManagerAccessor
	Get
	Set
```

### Property Value

Type: [IRegionManagerAccessor](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)  
The region manager accessor.

## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)  
[DelayedRegionCreationBehavior Members](/patterns-practices/reference/delayedregioncreationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)<br/>