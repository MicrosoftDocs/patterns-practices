---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, Uri, NavigationParameters)'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Uri,Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736220(v=PandP.50)'
---


# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, NavigationParameters)

This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public static void RequestNavigate( this IRegionManager regionManager, string regionName, Uri target, NavigationParameters navigationParameters )&lt;ExtensionAttribute&gt; Public Shared Sub RequestNavigate ( regionManager As IRegionManager, regionName As String, target As Uri, navigationParameters As NavigationParameters )

### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager)
The IRegionManager instance that is extended by this method.

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the region where the navigation will occur.

target  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)
A Uri that represents the target where the region will navigate.

navigationParameters  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationparameters)
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[RegionManagerExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[RequestNavigate Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
