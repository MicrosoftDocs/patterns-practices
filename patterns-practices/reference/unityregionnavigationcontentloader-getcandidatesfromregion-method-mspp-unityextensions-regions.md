---
TOCTitle: GetCandidatesFromRegion Method
Title: 'UnityRegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.UnityExtensions.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.UnityExtensions.Regions.UnityRegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'unityregionnavigationcontentloader-getcandidatesfromregion-method-mspp-unityextensions-regions.md'
---

# UnityRegionNavigationContentLoader.GetCandidatesFromRegion Method

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.UnityExtensions.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.regions)
**Assembly:** Microsoft.Practices.Prism.UnityExtensions (in Microsoft.Practices.Prism.UnityExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
protected override IEnumerable&lt;Object&gt; GetCandidatesFromRegion( IRegion region, string candidateNavigationContract )Protected Overrides Function GetCandidatesFromRegion ( region As IRegion, candidateNavigationContract As String ) As IEnumerable(Of Object)

### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)
The region containing items that may satisfy the navigation request.

candidateNavigationContract  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
An enumerable of candidate objects from the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)

## See Also
[UnityRegionNavigationContentLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.regions.unityregionnavigationcontentloader)

[UnityRegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.unityextensions.regions.unityregionnavigationcontentloader)

[Microsoft.Practices.Prism.UnityExtensions.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.unityextensions.regions)
