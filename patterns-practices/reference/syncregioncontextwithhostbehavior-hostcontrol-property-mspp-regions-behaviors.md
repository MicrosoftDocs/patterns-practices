---
TOCTitle: HostControl Property
Title: 'SyncRegionContextWithHostBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior.HostControl'
ms:mtpsurl: 'syncregioncontextwithhostbehavior-hostcontrol-property-mspp-regions-behaviors.md'
---

# SyncRegionContextWithHostBehavior.HostControl Property

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
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to. This is usually a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) that is part of the tree.

### Implements

[IHostAwareRegionBehavior.HostControl](/patterns-practices/reference/ihostawareregionbehavior-hostcontrol-property-mspp-regions-behaviors)

## See Also

[SyncRegionContextWithHostBehavior Class](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors)  
[SyncRegionContextWithHostBehavior Members](/patterns-practices/reference/syncregioncontextwithhostbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  