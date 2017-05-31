---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, String, NavigationParameters)'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.String,Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions.md'
---

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, NavigationParameters)

This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C# 
public static void RequestNavigate(
	this IRegionManager regionManager,
	string regionName,
	string target,
	NavigationParameters navigationParameters
)
```

```VB 
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	regionManager As IRegionManager,
	regionName As String,
	target As String,
	navigationParameters As NavigationParameters
)
```

### Parameters

*regionManager*

Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/mspp-regions-namespace.iregionmanager)

The IRegionManager instance that is extended by this method.

*regionName*  

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the region where the navigation will occur.

*target*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

A string that represents the target where the region will navigate.

*navigationParameters*

Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/mspp-regions-namespace.navigationparameters)

An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](/patterns-practices/reference/mspp-regions-namespace.iregionmanager). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).


## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/mspp-regions-namespace.regionmanagerextensions)

[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)

[RequestNavigate Overload](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)