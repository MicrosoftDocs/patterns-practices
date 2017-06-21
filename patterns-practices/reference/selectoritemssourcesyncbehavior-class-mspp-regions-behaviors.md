---
TOCTitle: SelectorItemsSourceSyncBehavior Class
Title: 'SelectorItemsSourceSyncBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior'
ms:mtpsurl: 'selectoritemssourcesyncbehavior-class-mspp-regions-behaviors.md'
---


# SelectorItemsSourceSyncBehavior Class

Defines the attached behavior that keeps the items of the [Selector](http://msdn.microsoft.com/en-us/library/ms595227) host control in synchronization with the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions). This behavior also makes sure that, if you activate a view in a region, the SelectedItem is set. If you set the SelectedItem or SelectedItems (ListBox) then this behavior will also call Activate on the selected items.

## Remarks

 When calling Activate on a view, you can only select a single active view at a time. By setting the SelectedItems property of a listbox, you can set multiple views to active.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public class SelectorItemsSourceSyncBehavior : RegionBehavior, 
	IHostAwareRegionBehavior, IRegionBehavior
```

```VB
'Declaration
Public Class SelectorItemsSourceSyncBehavior
	Inherits RegionBehavior
	Implements IHostAwareRegionBehavior, IRegionBehavior
```

### Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
    Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior  
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSelectorItemsSourceSyncBehavior](/patterns-practices/reference/mefselectoritemssourcesyncbehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[SelectorItemsSourceSyncBehavior Members](/patterns-practices/reference/selectoritemssourcesyncbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
