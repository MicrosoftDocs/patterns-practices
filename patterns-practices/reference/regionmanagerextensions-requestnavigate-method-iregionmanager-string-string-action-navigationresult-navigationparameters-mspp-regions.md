---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult), NavigationParameters)'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736247(v=PandP.50)'
---

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action&lt;NavigationResult&gt;, NavigationParameters)

This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) 

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
	public static void RequestNavigate(
	this IRegionManager regionManager,
	string regionName,
	string target,
	Action<NavigationResult> navigationCallback,
	NavigationParameters navigationParameters
)
```

### Parameters

*regionManager*

Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)<br/>
The IRegionManager instance that is extended by this method.

*regionName*  

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the region where the navigation will occur.

*target*  

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
A string that represents the target where the region will navigate.

*navigationCallback*  

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)><br/>
The navigation callback that will be executed after the navigation is completed.

*navigationParameters*

Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)<br/>
An instance of NavigationParameters, which holds a collection of object parameters.

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, String, Action(Of NavigationResult), NavigationParameters)

This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) 

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
	'Declaration
	<ExtensionAttribute> 
	Public Shared Sub RequestNavigate ( 
	regionManager As IRegionManager,
	regionName As String,
	target As String,
	navigationCallback As Action(Of NavigationResult),
	navigationParameters As NavigationParameters
)
```

### Parameters

*regionManager*

Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)<br/>
The IRegionManager instance that is extended by this method.

*regionName*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the region where the navigation will occur.

*target*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
A string that represents the target where the region will navigate.

*navigationCallback*

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions))<br/>
The navigation callback that will be executed after the navigation is completed.

*navigationParameters*

Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)<br/>
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](https://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)

[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)

[RequestNavigate Overload](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
