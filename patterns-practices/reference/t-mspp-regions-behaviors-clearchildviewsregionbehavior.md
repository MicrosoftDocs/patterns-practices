---
TOCTitle: ClearChildViewsRegionBehavior Class
Title: 'ClearChildViewsRegionBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.ClearChildViewsRegionBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683932(v=PandP.50)'
---

Prism Class Library

ClearChildViewsRegionBehavior Class
===================================

Behavior that removes the RegionManager attached property of all the views in a region once the RegionManager property of a region becomes null. This is useful when removing views with nested regions, to ensure these nested regions get removed from the RegionManager as well.
Remarks
-------

<span id="remarksToggle"></span> This behavior does not apply by default. In order to activate it, the ClearChildViews attached property must be set to True in the view containing the affected child regions.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public class ClearChildViewsRegionBehavior : RegionBehaviorPublic Class ClearChildViewsRegionBehavior Inherits RegionBehavior

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions..::.RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior)
    Microsoft.Practices.Prism.Regions.Behaviors..::.ClearChildViewsRegionBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors..::.MefClearChildViewsRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefclearchildviewsregionbehavior)

See Also
--------

<span id="seeAlsoToggle"></span>
[ClearChildViewsRegionBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.clearchildviewsregionbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
