---
TOCTitle: 'RegisterViewWithRegion Method (IRegionManager, String, Type)'
Title: 'RegionManagerExtensions.RegisterViewWithRegion Method (IRegionManager, String, Type) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RegisterViewWithRegion(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418954(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions.RegisterViewWithRegion Method (IRegionManager, String, Type)
========================================================================================

Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static IRegionManager RegisterViewWithRegion( this IRegionManager regionManager, string regionName, Type viewType )&lt;ExtensionAttribute&gt; Public Shared Function RegisterViewWithRegion ( regionManager As IRegionManager, regionName As String, viewType As Type ) As IRegionManager

### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The regionmanager that this extension method effects.

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the region to associate the view with.

viewType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type of the view to register with the

### Return Value

Type: [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The regionmanager, for adding several views easily
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

See Also
--------


[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegisterViewWithRegion Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
