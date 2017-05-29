---
TOCTitle: Regions Property
Title: 'RegionManager.Regions Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.RegionManager.Regions'
ms:mtpsurl: 'regionmanager-regions-property-mspp-regions.md'
---

# RegionManager.Regions Property

Gets a collection of [IRegion](iregion-interface-mspp-regions) that identify each region by name. You can use this collection to add or remove regions to the current region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
    public IRegionCollection Regions { get; }
```
```VB
    'Declaration
     Public ReadOnly Property Regions As IRegionCollection 
     Get
```
public IRegionCollection Regions { get; }Public ReadOnly Property Regions As IRegionCollection Get
### Property Value

Type: [IRegionCollection](iregioncollection-interface-mspp-regions)

A [IRegionCollection](iregioncollection-interface-mspp-regions) with all the registered regions.
### Implements

[IRegionManager.Regions](iregionmanager-regions-property-mspp-regions)

## See Also
[RegionManager Class](regionmanager-class-mspp-regions)

[RegionManager Members](regionmanager-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace)
