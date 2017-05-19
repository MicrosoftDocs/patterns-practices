---
TOCTitle: SelectorItemsSourceSyncBehavior Class
Title: 'SelectorItemsSourceSyncBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431519(v=PandP.50)'
---

Prism Class Library

SelectorItemsSourceSyncBehavior Class
=====================================

Defines the attached behavior that keeps the items of the [Selector](http://msdn.microsoft.com/en-us/library/ms595227) host control in synchronization with the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion). This behavior also makes sure that, if you activate a view in a region, the SelectedItem is set. If you set the SelectedItem or SelectedItems (ListBox) then this behavior will also call Activate on the selected items.
Remarks
-------

<span id="remarksToggle"></span> When calling Activate on a view, you can only select a single active view at a time. By setting the SelectedItems property of a listbox, you can set multiple views to active.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class SelectorItemsSourceSyncBehavior : RegionBehavior, IHostAwareRegionBehavior, IRegionBehaviorPublic Class SelectorItemsSourceSyncBehavior Inherits RegionBehavior Implements IHostAwareRegionBehavior, IRegionBehavior

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions.RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior)
    Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSelectorItemsSourceSyncBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefselectoritemssourcesyncbehavior)

See Also
--------


[SelectorItemsSourceSyncBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.selectoritemssourcesyncbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
