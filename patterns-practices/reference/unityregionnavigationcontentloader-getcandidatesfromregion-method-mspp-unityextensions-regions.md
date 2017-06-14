---
TOCTitle: GetCandidatesFromRegion Method
Title: 'UnityRegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.UnityExtensions.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.Regions.UnityRegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'unityregionnavigationcontentloader-getcandidatesfromregion-method-mspp-unityextensions-regions.md'
---


# UnityRegionNavigationContentLoader.GetCandidatesFromRegion Method

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions.Regions](/patterns-practices/reference/mspp-unityextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override IEnumerable<Object> GetCandidatesFromRegion(
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

The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

## Syntax

```VB
'Declaration
Protected Overrides Function GetCandidatesFromRegion ( 
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

The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

## See Also

[UnityRegionNavigationContentLoader Class](/patterns-practices/reference/unityregionnavigationcontentloader-class-mspp-unityextensions-regions)  
[UnityRegionNavigationContentLoader Members](/patterns-practices/reference/unityregionnavigationcontentloader-members-mspp-unityextensions-regions)  
[Microsoft.Practices.Prism.UnityExtensions.Regions Namespace](/patterns-practices/reference/mspp-unityextensions-regions-namespace)  