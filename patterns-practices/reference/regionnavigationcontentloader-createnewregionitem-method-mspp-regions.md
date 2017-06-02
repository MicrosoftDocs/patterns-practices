---
TOCTitle: CreateNewRegionItem Method
Title: 'RegionNavigationContentLoader.CreateNewRegionItem Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.CreateNewRegionItem(System.String)'
ms:mtpsurl: 'regionnavigationcontentloader-createnewregionitem-method-mspp-regions.md'
---
# RegionNavigationContentLoader.CreateNewRegionItem Method

Provides a new item for the region based on the supplied candidate target contract name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual Object CreateNewRegionItem(
	string candidateTargetContract
)
```

```VB
'Declaration
Protected Overridable Function CreateNewRegionItem ( 
	candidateTargetContract As String
) As Object
```

### Parameters

*candidateTargetContract*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The target contract to build.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
An instance of an item to put into the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

## See Also

[RegionNavigationContentLoader Class](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)  
[RegionNavigationContentLoader Members](/patterns-practices/reference/regionnavigationcontentloader-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)


