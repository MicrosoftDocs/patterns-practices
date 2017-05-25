---
TOCTitle: RegionManagerProperty Field
Title: 'RegionManager.RegionManagerProperty Field (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'F:Microsoft.Practices.Prism.Regions.RegionManager.RegionManagerProperty'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430968(v=PandP.50)'
---


# RegionManager.RegionManagerProperty Field

Identifies the RegionManager attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public static readonly DependencyProperty RegionManagerPropertyPublic Shared ReadOnly RegionManagerProperty As DependencyProperty
### Field Value

Type: [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318)

## Remarks

 When a control has both the [RegionNameProperty](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanager.regionnameproperty) and RegionManagerProperty attached properties set to a value different than nullNothingnullptra null reference (Nothing in Visual Basic) and there is a [IRegionAdapter](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter) mapping registered for the control, it will create and adapt a new region for that control, and register it in the [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) with the specified region name.

## See Also

[RegionManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
