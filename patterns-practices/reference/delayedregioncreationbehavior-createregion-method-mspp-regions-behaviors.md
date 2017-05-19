---
TOCTitle: CreateRegion Method
Title: 'DelayedRegionCreationBehavior.CreateRegion Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.CreateRegion(System.Windows.DependencyObject,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405939(v=PandP.50)'
---

Prism Class Library

DelayedRegionCreationBehavior.CreateRegion Method
=====================================================

Method that will create the region, by calling the right [IRegionAdapter](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionadapter).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual IRegion CreateRegion( DependencyObject targetElement, string regionName )Protected Overridable Function CreateRegion ( targetElement As DependencyObject, regionName As String ) As IRegion
#### Parameters

targetElement  
Type: [System.Windows.DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)
The target element that will host the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion).

regionName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
Name of the region.

#### Return Value

Type: [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)
The created [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

See Also
--------


[DelayedRegionCreationBehavior Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[DelayedRegionCreationBehavior Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
