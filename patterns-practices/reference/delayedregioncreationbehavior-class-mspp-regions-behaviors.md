---
TOCTitle: DelayedRegionCreationBehavior Class
Title: 'DelayedRegionCreationBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431513(v=PandP.50)'
---

Prism Class Library

DelayedRegionCreationBehavior Class
===================================

Behavior that creates a new [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion), when the control that will host the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) (see [TargetElement](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement)) is added to the VisualTree. This behavior will use the [RegionAdapterMappings](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadaptermappings) class to find the right type of adapter to create the region. After the region is created, this behavior will detach.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class DelayedRegionCreationBehaviorPublic Class DelayedRegionCreationBehavior

Remarks
-------

<span id="remarksToggle"></span> Attached property value inheritance is not available in Silverlight, so the current approach walks up the visual tree when requesting a region from a region manager. The [RegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior) is now responsible for walking up the Tree.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior
    [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefDelayedRegionCreationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefdelayedregioncreationbehavior)

See Also
--------


[DelayedRegionCreationBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
