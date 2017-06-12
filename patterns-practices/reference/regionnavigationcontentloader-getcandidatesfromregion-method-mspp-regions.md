---
TOCTitle: GetCandidatesFromRegion Method
Title: 'RegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'regionnavigationcontentloader-getcandidatesfromregion-method-mspp-regions.md'
---
# RegionNavigationContentLoader.GetCandidatesFromRegion Method

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual IEnumerable<Object> GetCandidatesFromRegion(
	IRegion region,
	string candidateNavigationContract
)
```

### Parameters

*region*  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region containing items that may satisfy the navigation request.

*candidateNavigationContract*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The candidate navigation target as determined by [GetContractFromNavigationContext(NavigationContext)](/patterns-practices/reference/regionnavigationcontentloader-getcontractfromnavigationcontext-method-mspp-regions)

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;  
An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)


```VB
'Declaration
Protected Overridable Function GetCandidatesFromRegion ( 
	region As IRegion,
	candidateNavigationContract As String
) As IEnumerable(Of Object)
```

### Parameters

*region*  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region containing items that may satisfy the navigation request.

*candidateNavigationContract*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The candidate navigation target as determined by [GetContractFromNavigationContext(NavigationContext)](/patterns-practices/reference/regionnavigationcontentloader-getcontractfromnavigationcontext-method-mspp-regions)

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))  
An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

## See Also

[RegionNavigationContentLoader Class](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)  
[RegionNavigationContentLoader Members](/patterns-practices/reference/regionnavigationcontentloader-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>