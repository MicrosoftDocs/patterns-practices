---
TOCTitle: Attach Method
Title: 'DelayedRegionCreationBehavior.Attach Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.Attach'
ms:mtpsurl: 'delayedregioncreationbehavior-attach-method-mspp-regions-behaviors.md'
---

# DelayedRegionCreationBehavior.Attach Method

Start monitoring the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) and the [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors) to detect when the [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors) becomes part of the Visual Tree. When that happens, the Region will be created and the behavior will [Detach()](/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public void Attach()
```

```VB
'Declaration
Public Sub Attach
```
## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)  
[DelayedRegionCreationBehavior Members](/patterns-practices/reference/delayedregioncreationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  