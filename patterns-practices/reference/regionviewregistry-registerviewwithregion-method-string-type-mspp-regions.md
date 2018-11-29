---
TOCTitle: 'RegisterViewWithRegion Method (String, Type)'
Title: 'RegionViewRegistry.RegisterViewWithRegion Method (String, Type) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.RegisterViewWithRegion(System.String,System.Type)'
ms:mtpsurl: 'regionviewregistry-registerviewwithregion-method-mspp-regions.md'
---

# RegionViewRegistry.RegisterViewWithRegion Method (String, Type)

Registers a content type with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RegisterViewWithRegion(
	string regionName,
	Type viewType
)
```

```VB
'Declaration
Public Sub RegisterViewWithRegion ( 
	regionName As String,
	viewType As Type
)
```

### Parameters

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Region name to which the *viewType* will be registered.

*viewType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Content type to be registered for the *regionName*.

### Implements

[IRegionViewRegistry.RegisterViewWithRegion(String, Type)](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-string-type-mspp-regions)

## See Also

[RegionViewRegistry Class](/patterns-practices/reference/regionviewregistry-class-mspp-regions)  
[RegionViewRegistry Members](/patterns-practices/reference/regionviewregistry-members-mspp-regions)  
[RegisterViewWithRegion Overload](/patterns-practices/reference/regionviewregistry-registerviewwithregion-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  