---
TOCTitle: RegionManager Property
Title: 'Region.RegionManager Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.Region.RegionManager'
ms:mtpsurl: 'region-regionmanager-property-mspp-regions.md'
---


# Region.RegionManager Property

Gets or sets the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public IRegionManager RegionManager { get; set; }
```
```VB
'Declaration
Public Property RegionManager As IRegionManager
	Get
	Set
```
### Property Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)   
The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) where this [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is registered.
### Implements

[IRegion.RegionManager](/patterns-practices/reference/iregion-regionmanager-property-mspp-regions)

## Remarks

This is usually used by implementations of [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) and should not be used by the developer explicitely.

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)

[Region Class](/patterns-practices/reference/region-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
