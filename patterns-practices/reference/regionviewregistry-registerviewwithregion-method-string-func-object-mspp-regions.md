---
TOCTitle: 'RegisterViewWithRegion Method (String, Func(Object))'
Title: 'RegionViewRegistry.RegisterViewWithRegion Method (String, Func(Object)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.RegisterViewWithRegion(System.String,System.Func{System.Object})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg406468(v=PandP.50)'
---


# RegionViewRegistry.RegisterViewWithRegion Method (String, Func&lt;(Of &lt;(Object&gt;)&gt;))

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public void RegisterViewWithRegion( string regionName, Func&lt;Object&gt; getContentDelegate )Public Sub RegisterViewWithRegion ( regionName As String, getContentDelegate As Func(Of Object) )

### Parameters

regionName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Region name to which the getContentDelegate will be registered.

getContentDelegate  
Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;(Of &lt;([Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;)&gt;)
Delegate used to retrieve the content associated with the regionName.

### Implements

[IRegionViewRegistry.RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry.registerviewwithregion(system.string%2csystem.func%7bsystem.object%7d))

## See Also

[RegionViewRegistry Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionviewregistry)

[RegionViewRegistry Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionviewregistry)

[RegisterViewWithRegion Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.regionviewregistry.registerviewwithregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
