---
TOCTitle: RegionNameProperty Field
Title: 'RegionManager.RegionNameProperty Field (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'F:Microsoft.Practices.Prism.Regions.RegionManager.RegionNameProperty'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430969(v=PandP.50)'
---

Prism Class Library

RegionManager.RegionNameProperty Field
==========================================

Identifies the RegionName attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static readonly DependencyProperty RegionNamePropertyPublic Shared ReadOnly RegionNameProperty As DependencyProperty
#### Field Value

Type: [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318)

Remarks
-------

<span id="remarksToggle"></span> When a control has both the RegionNameProperty and [RegionManagerProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty) attached properties set to a value different than nullNothingnullptra null reference (Nothing in Visual Basic) and there is a [IRegionAdapter](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionadapter) mapping registered for the control, it will create and adapt a new region for that control, and register it in the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) with the specified region name.

See Also
--------


[RegionManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
