---
TOCTitle: GetRegionName Method
Title: 'RegionManager.GetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionName(System.Windows.DependencyObject)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418964(v=PandP.50)'
---

Prism Class Library

RegionManager..::.GetRegionName Method
======================================

Gets the value for the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static string GetRegionName( DependencyObject regionTarget )Public Shared Function GetRegionName ( regionTarget As DependencyObject ) As String
#### Parameters

regionTarget  
Type: [System.Windows..::.DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)
The object to adapt. This is typically a container (i.e a control).

#### Return Value

Type: [String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name of the region that should be created when [RegionManagerProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty) is also set in this element.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
