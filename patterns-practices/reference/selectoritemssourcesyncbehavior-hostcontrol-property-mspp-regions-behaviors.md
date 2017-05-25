---
TOCTitle: HostControl Property
Title: 'SelectorItemsSourceSyncBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior.HostControl'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431334(v=PandP.50)'
---


# SelectorItemsSourceSyncBehavior.HostControl Property

Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) is attached to.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public DependencyObject HostControl { get; set; }Public Property HostControl As DependencyObject Get Set
### Property Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) is attached to.
### Implements

[IHostAwareRegionBehavior.HostControl](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.ihostawareregionbehavior.hostcontrol)

## Remarks

For this behavior, the host control must always be a [Selector](http://msdn.microsoft.com/en-us/library/ms595227) or an inherited class.

## See Also

[SelectorItemsSourceSyncBehavior Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.selectoritemssourcesyncbehavior)

[SelectorItemsSourceSyncBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.selectoritemssourcesyncbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
