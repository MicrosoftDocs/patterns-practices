---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult))'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions.md'
---


# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))

Navigates the specified region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RequestNavigate(
	this IRegionManager regionManager,
	string regionName,
	string source,
	Action<NavigationResult> navigationCallback
)
```

### Parameters

_regionManager_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The regionmanager that this extension method effects.

_regionName_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the region to call Navigate on.

_source_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The URI of the content to display.

_navigationCallback_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult)&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation callback.

## Syntax

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	regionManager As IRegionManager,
	regionName As String,
	source As String,
	navigationCallback As Action(Of NavigationResult)
)
```

### Parameters

_regionManager_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The regionmanager that this extension method effects.

_regionName_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the region to call Navigate on.

_source_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The URI of the content to display.

_navigationCallback_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult))  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation callback.


### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)<br/>
[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)<br/>
[RequestNavigate Overload](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>
