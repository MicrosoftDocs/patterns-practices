
---
TOCTitle: GetCandidatesFromRegion Method
Title: 'MefRegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'mefregionnavigationcontentloader-getcandidatesfromregion-method-mspp-mefextensions-regions.md'
---


# MefRegionNavigationContentLoader.GetCandidatesFromRegion Method

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

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
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/mspp-regions-namespace.iregion)
The region containing items that may satisfy the navigation request.

*candidateNavigationContract*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)
An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/mspp-regions-namespace.iregion)

## Syntax

```VB
protected override IEnumerable<Object> GetCandidatesFromRegion(
	IRegion region,
	string candidateNavigationContract
)
```

### Parameters

*region*  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/mspp-regions-namespace.iregion)
The region containing items that may satisfy the navigation request.

*candidateNavigationContract*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of ([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)))
An enumerable of candidate objects from the [IRegion](/patterns-practices/reference/mspp-regions-namespace.iregion)

## See Also

[MefRegionNavigationContentLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.mefregionnavigationcontentloader)

[MefRegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.regions.mefregionnavigationcontentloader)

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions)

