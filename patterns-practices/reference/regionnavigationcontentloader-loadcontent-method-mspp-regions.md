---
TOCTitle: LoadContent Method
Title: 'RegionNavigationContentLoader.LoadContent Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.LoadContent(Microsoft.Practices.Prism.Regions.IRegion,Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationcontentloader.loadcontent(v=pandp.50)'
---

Prism Class Library

RegionNavigationContentLoader.LoadContent Method
====================================================

Gets the view to which the navigation request represented by navigationContext applies.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public Object LoadContent( IRegion region, NavigationContext navigationContext )Public Function LoadContent ( region As IRegion, navigationContext As NavigationContext ) As Object

### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)
The region.

navigationContext  
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationcontext)
The context representing the navigation request.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The view to be the target of the navigation request.
### Implements

[IRegionNavigationContentLoader.LoadContent(IRegion, NavigationContext)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationcontentloader.loadcontent(microsoft.practices.prism.regions.iregion%2cmicrosoft.practices.prism.regions.navigationcontext))

Remarks
-------

 If none of the views in the region can be the target of the navigation request, a new view is created and added to the region.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                         | Condition                                                     |
|-----------------------------------------------------------------------------------|---------------------------------------------------------------|
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114) | when a new view cannot be created for the navigation request. |

See Also
--------


[RegionNavigationContentLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationcontentloader)

[RegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
