---
TOCTitle: CreateNewRegionItem Method
Title: 'RegionNavigationContentLoader.CreateNewRegionItem Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.CreateNewRegionItem(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418969(v=PandP.50)'
---

Prism Class Library

RegionNavigationContentLoader.CreateNewRegionItem Method
============================================================

Provides a new item for the region based on the supplied candidate target contract name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected virtual Object CreateNewRegionItem( string candidateTargetContract )Protected Overridable Function CreateNewRegionItem ( candidateTargetContract As String ) As Object
#### Parameters

candidateTargetContract  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The target contract to build.

#### Return Value

Type: [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
An instance of an item to put into the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion).

See Also
--------


[RegionNavigationContentLoader Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[RegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
