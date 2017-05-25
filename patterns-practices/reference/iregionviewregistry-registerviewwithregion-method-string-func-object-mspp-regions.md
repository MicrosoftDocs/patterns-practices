---
TOCTitle: 'RegisterViewWithRegion Method (String, Func(Object))'
Title: 'IRegionViewRegistry.RegisterViewWithRegion Method (String, Func(Object)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.RegisterViewWithRegion(System.String,System.Func{System.Object})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406466(v=PandP.50)'
---


# IRegionViewRegistry.RegisterViewWithRegion Method (String, Func&lt;(Of &lt;(Object&gt;)&gt;))

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

void RegisterViewWithRegion( string regionName, Func&lt;Object&gt; getContentDelegate )Sub RegisterViewWithRegion ( regionName As String, getContentDelegate As Func(Of Object) )

### Parameters

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Region name to which the getContentDelegate will be registered.

getContentDelegate  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
Delegate used to retrieve the content associated with the regionName.

## See Also

[IRegionViewRegistry Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry)

[IRegionViewRegistry Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregionviewregistry)

[RegisterViewWithRegion Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.iregionviewregistry.registerviewwithregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
