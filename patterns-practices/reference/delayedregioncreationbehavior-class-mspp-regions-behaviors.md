---
TOCTitle: DelayedRegionCreationBehavior Class
Title: 'DelayedRegionCreationBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior'
ms:mtpsurl: 'delayedregioncreationbehavior-class-mspp-regions-behaviors.md'
---


# DelayedRegionCreationBehavior Class

Behavior that creates a new [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions), when the control that will host the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) (see [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)) is added to the VisualTree. This behavior will use the [RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions) class to find the right type of adapter to create the region. After the region is created, this behavior will detach.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class DelayedRegionCreationBehavior
```

```VB
'Declaration
Public Class DelayedRegionCreationBehavior
```

## Remarks

 Attached property value inheritance is not available in Silverlight, so the current approach walks up the visual tree when requesting a region from a region manager. The [RegionManagerRegistrationBehavior](/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors) is now responsible for walking up the Tree.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior  
    [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior](/patterns-practices/reference/mefdelayedregioncreationbehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[DelayedRegionCreationBehavior Members](/patterns-practices/reference/delayedregioncreationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  