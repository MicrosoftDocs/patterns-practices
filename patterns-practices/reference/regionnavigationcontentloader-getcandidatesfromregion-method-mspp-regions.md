---
TOCTitle: GetCandidatesFromRegion Method
Title: 'RegionNavigationContentLoader.GetCandidatesFromRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetCandidatesFromRegion(Microsoft.Practices.Prism.Regions.IRegion,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationcontentloader.getcandidatesfromregion(v=pandp.50)'
---

Prism Class Library

RegionNavigationContentLoader.GetCandidatesFromRegion Method
================================================================

Returns the set of candidates that may satisfiy this navigation request.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected virtual IEnumerable&lt;Object&gt; GetCandidatesFromRegion( IRegion region, string candidateNavigationContract )Protected Overridable Function GetCandidatesFromRegion ( region As IRegion, candidateNavigationContract As String ) As IEnumerable(Of Object)

### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)
The region containing items that may satisfy the navigation request.

candidateNavigationContract  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The candidate navigation target as determined by [GetContractFromNavigationContext(NavigationContext)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationcontentloader.getcontractfromnavigationcontext(microsoft.practices.prism.regions.navigationcontext))

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
An enumerable of candidate objects from the [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)

See Also
--------


[RegionNavigationContentLoader Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionnavigationcontentloader)

[RegionNavigationContentLoader Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionnavigationcontentloader)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
