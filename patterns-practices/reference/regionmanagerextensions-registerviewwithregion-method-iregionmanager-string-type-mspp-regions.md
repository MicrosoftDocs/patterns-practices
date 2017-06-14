---
TOCTitle: 'RegisterViewWithRegion Method (IRegionManager, String, Type)'
Title: 'RegionManagerExtensions.RegisterViewWithRegion Method (IRegionManager, String, Type) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RegisterViewWithRegion(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Type)'
ms:mtpsurl: 'regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions.md'
---


# RegionManagerExtensions.RegisterViewWithRegion Method (IRegionManager, String, Type)

Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static IRegionManager RegisterViewWithRegion(
	this IRegionManager regionManager,
	string regionName,
	Type viewType
)
```
```VB
'Declaration
<ExtensionAttribute> 
Public Shared Function RegisterViewWithRegion ( 
	regionManager As IRegionManager,
	regionName As String,
	viewType As Type
) As IRegionManager
```
### Parameters

_regionManager_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The regionmanager that this extension method effects.

_regionName_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the region to associate the view with.

_viewType_  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type of the view to register with the

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
The regionmanager, for adding several views easily
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)<br/>
[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)<br/>
[RegisterViewWithRegion Overload](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>