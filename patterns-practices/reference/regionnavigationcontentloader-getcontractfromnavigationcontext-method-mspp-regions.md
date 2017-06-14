---
TOCTitle: GetContractFromNavigationContext Method
Title: 'RegionNavigationContentLoader.GetContractFromNavigationContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetContractFromNavigationContext(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'regionnavigationcontentloader-getcontractfromnavigationcontext-method-mspp-regions.md'
---

# RegionNavigationContentLoader.GetContractFromNavigationContext Method

Returns the candidate TargetContract based on the [NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual string GetContractFromNavigationContext(
	NavigationContext navigationContext
)
```

```VB
'Declaration
Protected Overridable Function GetContractFromNavigationContext ( 
	navigationContext As NavigationContext
) As String
```

### Parameters

*navigationContext*

 Type: [Microsoft.Practices.Prism.Regions.NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions)
 
 The navigation contract.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The candidate contract to seek within the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) and to use, if not found, when resolving from the container.

## See Also

[RegionNavigationContentLoader Class](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)  
[RegionNavigationContentLoader Members](/patterns-practices/reference/regionnavigationcontentloader-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  