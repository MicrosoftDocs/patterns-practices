---
TOCTitle: GetContractFromNavigationContext Method
Title: 'RegionNavigationContentLoader.GetContractFromNavigationContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetContractFromNavigationContext(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418971(v=PandP.50)'
---

Prism Class Library

RegionNavigationContentLoader..::.GetContractFromNavigationContext Method
=========================================================================

Returns the candidate TargetContract based on the [NavigationContext](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationcontext).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual string GetContractFromNavigationContext( NavigationContext navigationContext )Protected Overridable Function GetContractFromNavigationContext ( navigationContext As NavigationContext ) As String
#### Parameters

navigationContext  
Type: [Microsoft.Practices.Prism.Regions..::.NavigationContext](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationcontext)
The navigation contract.

#### Return Value

Type: [String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The candidate contract to seek within the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) and to use, if not found, when resolving from the container.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionNavigationContentLoader Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[RegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
