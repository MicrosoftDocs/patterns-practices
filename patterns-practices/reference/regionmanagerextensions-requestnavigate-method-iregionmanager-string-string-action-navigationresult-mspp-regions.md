---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult))'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418958(v=PandP.50)'
---


# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))

Navigates the specified region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public static void RequestNavigate( this IRegionManager regionManager, string regionName, string source, Action&lt;NavigationResult&gt; navigationCallback )&lt;ExtensionAttribute&gt; Public Shared Sub RequestNavigate ( regionManager As IRegionManager, regionName As String, source As String, navigationCallback As Action(Of NavigationResult) )

### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager)
The regionmanager that this extension method effects.

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the region to call Navigate on.

source  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The URI of the content to display.

navigationCallback  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult)&gt;)&gt;)
The navigation callback.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[RegionManagerExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[RequestNavigate Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
