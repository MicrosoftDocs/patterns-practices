---
TOCTitle: HostControl Property
Title: 'RegionManagerRegistrationBehavior.HostControl Property (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior.HostControl'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431331(v=PandP.50)'
---

Prism Class Library

RegionManagerRegistrationBehavior.HostControl Property
==========================================================

Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) is attached to.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public DependencyObject HostControl { get; set; }Public Property HostControl As DependencyObject Get Set
### Property Value

Type: [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)
A [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) is attached to. This is usually a [FrameworkElement](http://msdn.microsoft.com/en-us/library/ms602714) that is part of the tree.
### Implements

[IHostAwareRegionBehavior.HostControl](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.ihostawareregionbehavior.hostcontrol)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                 | Condition                                                                                                                                                        |
|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | When this member is set after the [Attach()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior.attach) method has being called. |

See Also
--------


[RegionManagerRegistrationBehavior Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior)

[RegionManagerRegistrationBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors)
