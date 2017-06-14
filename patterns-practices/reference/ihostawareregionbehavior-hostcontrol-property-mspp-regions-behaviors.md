---
TOCTitle: HostControl Property
Title: 'IHostAwareRegionBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.IHostAwareRegionBehavior.HostControl'
ms:mtpsurl: 'ihostawareregionbehavior-hostcontrol-property-mspp-regions-behaviors.md'
---

# IHostAwareRegionBehavior.HostControl Property

Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
DependencyObject HostControl { get; set; }
```

```VB
'Declaration
Property HostControl As DependencyObject
	Get
	Set
```

### Property Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to. This is usually a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) that is part of the tree.

## See Also

[IHostAwareRegionBehavior Interface](/patterns-practices/reference/ihostawareregionbehavior-interface-mspp-regions-behaviors)  
[IHostAwareRegionBehavior Members](/patterns-practices/reference/ihostawareregionbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  