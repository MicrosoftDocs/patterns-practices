---
TOCTitle: HostControl Property
Title: 'RegionManagerRegistrationBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior.HostControl'
ms:mtpsurl: 'regionmanagerregistrationbehavior-hostcontrol-property-mspp-regions-behaviors.md'
---

# RegionManagerRegistrationBehavior.HostControl Property

Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public DependencyObject HostControl { get; set; }
```

### Property Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to. This is usually a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) that is part of the tree.

### Implements

[IHostAwareRegionBehavior.HostControl](/patterns-practices/reference/ihostawareregionbehavior-hostcontrol-property-mspp-regions-behaviors)

## Exceptions

| Exception | Condition |
|---|---|
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | When this member is set after the [Attach()](/patterns-practices/reference/iregionbehavior-attach-method-mspp-regions) method has being called. |

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

## Exceptions

| Exception | Condition |
|---|---|
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | When this member is set after the [Attach](/patterns-practices/reference/iregionbehavior-attach-method-mspp-regions) method has being called. |

## See Also

[RegionManagerRegistrationBehavior Class](/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors)  
[RegionManagerRegistrationBehavior Members](/patterns-practices/reference/regionmanagerregistrationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  