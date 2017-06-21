---
TOCTitle: 'RegisterViewWithRegion Method (String, Type)'
Title: 'IRegionViewRegistry.RegisterViewWithRegion Method (String, Type) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.RegisterViewWithRegion(System.String,System.Type)'
ms:mtpsurl: 'iregionviewregistry-registerviewwithregion-method-mspp-regions.md'
---


# IRegionViewRegistry.RegisterViewWithRegion Method (String, Type)

Registers a content type with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
void RegisterViewWithRegion(
	string regionName,
	Type viewType
)
```

```VB
'Declaration
Sub RegisterViewWithRegion ( 
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

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)  
[IRegionViewRegistry Members](/patterns-practices/reference/iregionviewregistry-members-mspp-regions)  
[RegisterViewWithRegion Overload](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  