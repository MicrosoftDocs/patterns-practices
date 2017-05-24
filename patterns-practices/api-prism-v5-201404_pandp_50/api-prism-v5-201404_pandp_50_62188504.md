---
TOCTitle: RegionManagerRegistrationBehavior Class
Title: 'RegionManagerRegistrationBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431517(v=PandP.50)'
---

Prism Class Library

RegionManagerRegistrationBehavior Class
=======================================

Subscribes to a static event from the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) in order to register the target [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) in a [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty) property is not nullNothingnullptra null reference (Nothing in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public class RegionManagerRegistrationBehavior : RegionBehavior, IHostAwareRegionBehavior, IRegionBehaviorPublic Class RegionManagerRegistrationBehavior Inherits RegionBehavior Implements IHostAwareRegionBehavior, IRegionBehavior

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions..::.RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior)
    Microsoft.Practices.Prism.Regions.Behaviors..::.RegionManagerRegistrationBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors..::.MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior)

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManagerRegistrationBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
