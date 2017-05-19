---
TOCTitle: RegionManager Property
Title: 'Region.RegionManager Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Region.RegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431392(v=PandP.50)'
---

Prism Class Library

Region.RegionManager Property
=================================

Gets or sets the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public IRegionManager RegionManager { get; set; }Public Property RegionManager As IRegionManager Get Set
#### Property Value

Type: [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) where this [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) is registered.
#### Implements

[IRegion.RegionManager](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.regionmanager)

Remarks
-------

<span id="remarksToggle"></span>This is usually used by implementations of [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) and should not be used by the developer explicitely.

See Also
--------


[Region Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region)

[Region Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.region)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
