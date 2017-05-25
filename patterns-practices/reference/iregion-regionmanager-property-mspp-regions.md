---
TOCTitle: RegionManager Property
Title: 'IRegion.RegionManager Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.IRegion.RegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431353(v=PandP.50)'
---


# IRegion.RegionManager Property

Gets or sets the [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

IRegionManager RegionManager { get; set; }Property RegionManager As IRegionManager Get Set
### Property Value

Type: [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager)
The [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) where this [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) is registered.

## Remarks

This is usually used by implementations of [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) and should not be used by the developer explicitely.

## See Also

[IRegion Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)

[IRegion Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
