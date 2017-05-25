---
TOCTitle: Initialize Method
Title: 'IRegionAdapter.Initialize Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionAdapter.Initialize(System.Object,System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionadapter.initialize(v=pandp.50)'
---

Prism Class Library

IRegionAdapter.Initialize Method
====================================

Adapts an object and binds it to a new [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


IRegion Initialize( Object regionTarget, string regionName )Function Initialize ( regionTarget As Object, regionName As String ) As IRegion

### Parameters

regionTarget  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The object to adapt.

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name of the region to be created.

### Return Value

Type: [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)
The new instance of [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) that the regionTarget is bound to.

See Also
--------


[IRegionAdapter Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter)

[IRegionAdapter Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregionadapter)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
