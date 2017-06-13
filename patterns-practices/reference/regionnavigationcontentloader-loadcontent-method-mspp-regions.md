---
TOCTitle: LoadContent Method
Title: 'RegionNavigationContentLoader.LoadContent Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.LoadContent(Microsoft.Practices.Prism.Regions.IRegion,Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'regionnavigationcontentloader-loadcontent-method-mspp-regions.md'
---
# RegionNavigationContentLoader.LoadContent Method

Gets the view to which the navigation request represented by *navigationContext* applies.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public Object LoadContent(
	IRegion region,
	NavigationContext navigationContext
)
```

```VB
'Declaration
Public Function LoadContent ( 
	region As IRegion,
	navigationContext As NavigationContext
) As Object
```

### Parameters

*region*  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region.

*navigationContext*  
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)  
The context representing the navigation request.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The view to be the target of the navigation request.
### Implements

[IRegionNavigationContentLoader.LoadContent(IRegion, NavigationContext)](/patterns-practices/reference/iregionnavigationcontentloader-loadcontent-method-mspp-regions)

## Remarks

 If none of the views in the region can be the target of the navigation request, a new view is created and added to the region.

## Exceptions

| Exception | Condition |
|---|---|
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114) | when a new view cannot be created for the navigation request. |

## See Also

[RegionNavigationContentLoader Class](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)  
[RegionNavigationContentLoader Members](/patterns-practices/reference/regionnavigationcontentloader-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>

