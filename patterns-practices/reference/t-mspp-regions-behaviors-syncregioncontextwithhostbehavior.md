---
TOCTitle: SyncRegionContextWithHostBehavior Class
Title: 'SyncRegionContextWithHostBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431520(v=PandP.50)'
---

Prism Class Library

SyncRegionContextWithHostBehavior Class
=======================================

Behavior that synchronizes the [Context](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.context) property of a [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) with the control that hosts the Region. It does this by setting the [RegionContextProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty) Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public class SyncRegionContextWithHostBehavior : RegionBehavior, IHostAwareRegionBehavior, IRegionBehaviorPublic Class SyncRegionContextWithHostBehavior Inherits RegionBehavior Implements IHostAwareRegionBehavior, IRegionBehavior

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions..::.RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior)
    Microsoft.Practices.Prism.Regions.Behaviors..::.SyncRegionContextWithHostBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors..::.MefSyncRegionContextWithHostBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefsyncregioncontextwithhostbehavior)

See Also
--------

<span id="seeAlsoToggle"></span>
[SyncRegionContextWithHostBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
