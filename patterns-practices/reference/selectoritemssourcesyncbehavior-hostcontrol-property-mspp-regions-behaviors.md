---
TOCTitle: HostControl Property
Title: 'SelectorItemsSourceSyncBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior.HostControl'
ms:mtpsurl: 'selectoritemssourcesyncbehavior-hostcontrol-property-mspp-regions-behaviors.md'
---

# SelectorItemsSourceSyncBehavior.HostControl Property

Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public DependencyObject HostControl { get; set; }
```

```VB
'Declaration
Public Property HostControl As DependencyObject
	Get
	Set
```

### Property Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.

### Implements

[IHostAwareRegionBehavior.HostControl](/patterns-practices/reference/ihostawareregionbehavior-hostcontrol-property-mspp-regions-behaviors)

## Remarks

For this behavior, the host control must always be a [Selector](http://msdn.microsoft.com/en-us/library/ms595227) or an inherited class.

## See Also

[SelectorItemsSourceSyncBehavior Class](/patterns-practices/reference/selectoritemssourcesyncbehavior-class-mspp-regions-behaviors)  
[SelectorItemsSourceSyncBehavior Members](/patterns-practices/reference/selectoritemssourcesyncbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
