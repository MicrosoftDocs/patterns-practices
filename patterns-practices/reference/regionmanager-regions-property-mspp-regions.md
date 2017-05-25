---
TOCTitle: Regions Property
Title: 'RegionManager.Regions Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.RegionManager.Regions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431372(v=PandP.50)'
---


# RegionManager.Regions Property

Gets a collection of [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) that identify each region by name. You can use this collection to add or remove regions to the current region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))<br/>


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

Type: [IRegionCollection](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregioncollection(v=pandp.50))

A [IRegionCollection](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregioncollection(v=pandp.50)) with all the registered regions.
### Implements

[IRegionManager.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager.regions(v=pandp.50))

## See Also

[RegionManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager(v=pandp.50))

[RegionManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
