---
TOCTitle: GetContents Method
Title: 'RegionViewRegistry.GetContents Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.GetContents(System.String)'
ms:mtpsurl: 'regionviewregistry-getcontents-method-mspp-regions.md'
---

Prism Class Library

RegionViewRegistry.GetContents Method
=========================================

Returns the contents registered for a region.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public IEnumerable&lt;Object&gt; GetContents( string regionName )Public Function GetContents ( regionName As String ) As IEnumerable(Of Object)

### Parameters

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Name of the region which content is being requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
Collection of contents registered for the region.
### Implements

[IRegionViewRegistry.GetContents(String)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry.getcontents(system.string))

See Also
--------


[RegionViewRegistry Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionviewregistry)

[RegionViewRegistry Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionviewregistry)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
