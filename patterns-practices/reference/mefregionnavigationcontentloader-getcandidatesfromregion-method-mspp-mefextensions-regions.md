---
TOCTitle: GetCandidatesFromRegion Method
Title: 'MefRegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736192(v=PandP.50)'
---

Prism Class Library

MefRegionNavigationContentLoader.GetCandidatesFromRegion Method
===================================================================

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override IEnumerable&lt;Object&gt; GetCandidatesFromRegion( IRegion region, string candidateNavigationContract )Protected Overrides Function GetCandidatesFromRegion ( region As IRegion, candidateNavigationContract As String ) As IEnumerable(Of Object)

### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)
The region containing items that may satisfy the navigation request.

candidateNavigationContract  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The candidate navigation target.

### Return Value

Type: [IEnumerable](http://msdn2.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
An enumerable of candidate objects from the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

See Also
--------


[MefRegionNavigationContentLoader Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.mefregionnavigationcontentloader)

[MefRegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.regions.mefregionnavigationcontentloader)

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions)
