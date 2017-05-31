---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, Uri, Action(NavigationResult))'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions.md'
---

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, Action (Of (NavigationResult))

Navigates the specified region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public static void RequestNavigate( this IRegionManager regionManager, string regionName, Uri source, Action&lt;NavigationResult&gt; navigationCallback )&lt;ExtensionAttribute&gt; Public Shared Sub RequestNavigate ( regionManager As IRegionManager, regionName As String, source As Uri, navigationCallback As Action(Of NavigationResult) )

### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)
The regionmanager that this extension method effects.

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the region to call Navigate on.

source  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)
The URI of the content to display.

navigationCallback  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of ([NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)))
The navigation callback.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also
[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)

[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)

[RequestNavigate Overload](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
