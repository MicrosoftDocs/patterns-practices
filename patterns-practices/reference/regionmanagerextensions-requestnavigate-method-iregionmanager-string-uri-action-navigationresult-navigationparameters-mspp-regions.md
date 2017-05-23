---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, Uri, Action(NavigationResult), NavigationParameters)'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736129(v=PandP.50)'
---

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri, Action(Of NavigationResult), NavigationParameters)

This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RequestNavigate(
	this IRegionManager regionManager,
	string regionName,
	Uri target,
	Action<NavigationResult> navigationCallback,
	NavigationParameters navigationParameters
)
```
#### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50))

The IRegionManager instance that is extended by this method.

regionName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

The name of the region where the navigation will occur.

target  
Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)

A Uri that represents the target where the region will navigate.

navigationCallback  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationresult(v=pandp.50))&gt;

The navigation callback that will be executed after the navigation is completed.

navigationParameters  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationparameters(v=pandp.50))

An instance of NavigationParameters, which holds a collection of object parameters.

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	regionManager As IRegionManager,
	regionName As String,
	target As Uri,
	navigationCallback As Action(Of NavigationResult),
	navigationParameters As NavigationParameters
)
```
#### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50))

The IRegionManager instance that is extended by this method.

regionName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

The name of the region where the navigation will occur.

target  
Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)

A Uri that represents the target where the region will navigate.

navigationCallback  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationresult(v=pandp.50)))

The navigation callback that will be executed after the navigation is completed.

navigationParameters  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationparameters(v=pandp.50))

An instance of NavigationParameters, which holds a collection of object parameters.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50)). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](https://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also
[RegionManagerExtensions Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanagerextensions(v=pandp.50))

[RegionManagerExtensions Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanagerextensions_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
