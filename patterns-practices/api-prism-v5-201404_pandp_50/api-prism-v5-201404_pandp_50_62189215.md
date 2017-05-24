---
TOCTitle: RegionManagerProperty Field
Title: 'RegionManager.RegionManagerProperty Field (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'F:Microsoft.Practices.Prism.Regions.RegionManager.RegionManagerProperty'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430968(v=PandP.50)'
---

Prism Class Library

RegionManager..::.RegionManagerProperty Field
=============================================

Identifies the RegionManager attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static readonly DependencyProperty RegionManagerPropertyPublic Shared ReadOnly RegionManagerProperty As DependencyProperty
#### Field Value

Type: [DependencyProperty](http://msdn2.microsoft.com/en-us/library/ms589318)

Remarks
-------

<span id="remarksToggle"></span> When a control has both the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) and RegionManagerProperty attached properties set to a value different than nullNothingnullptra null reference (Nothing in Visual Basic) and there is a [IRegionAdapter](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionadapter) mapping registered for the control, it will create and adapt a new region for that control, and register it in the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) with the specified region name.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
