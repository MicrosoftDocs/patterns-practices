---
TOCTitle: Add Method
Title: 'RegionManagerExtensions.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.Add(Microsoft.Practices.Prism.Regions.IRegionCollection,System.String,Microsoft.Practices.Prism.Regions.IRegion)'
ms:mtpsurl: 'regionmanagerextensions-add-method-mspp-regions.md'
---


# RegionManagerExtensions.Add Method

Adds a region to the regionmanager with the name received as argument.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

~~~C#
public static void Add(
	this IRegionCollection regionCollection,
	string regionName,
	IRegion region
)
~~~
~~~VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub Add ( 
	regionCollection As IRegionCollection,
	regionName As String,
	region As IRegion
)
~~~

### Parameters

_regionCollection_  
Type: [Microsoft.Practices.Prism.Regions.IRegionCollection](/patterns-practices/reference/iregioncollection-interface-mspp-regions)  
The regionmanager's collection of regions.

_regionName_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name to be given to the region.

_region_  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region to be added to the regionmanager.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionCollection](/patterns-practices/reference/iregioncollection-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## Exceptions


| Exception                                                                             | Condition                                                                                                                                                                                                                  |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown if _region_ or _regionCollection_ is **null**a null reference (**Nothing** in Visual Basic)..                                                                                                                      |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | Thrown if _regionName_ and _region_'s name do not match and the _region_[Name](/patterns-practices/reference/iregion-name-property-mspp-regions) is not **null**a null reference (**Nothing** in Visual Basic). |

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)

[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
