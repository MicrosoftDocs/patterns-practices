---
TOCTitle: 'RegisterViewWithRegion Method (String, Type)'
Title: 'IRegionViewRegistry.RegisterViewWithRegion Method (String, Type) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.RegisterViewWithRegion(System.String,System.Type)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405975(v=PandP.50)'
---

Prism Class Library

IRegionViewRegistry.RegisterViewWithRegion Method (String, Type)
====================================================================

Registers a content type with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

Syntax
------

```C#
void RegisterViewWithRegion(
	string regionName,
	Type viewType
)
```

```VB
'Declaration
Sub RegisterViewWithRegion ( 
	regionName As String,
	viewType As Type
)
```

#### Parameters

*regionName*
  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
Region name to which the viewType will be registered.

*viewType*  

Type: [System.Type](http://msdn2.microsoft.com/en-us/library/42892f65)
Content type to be registered for the regionName.

See Also
--------


[IRegionViewRegistry Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionviewregistry(v=pandp.50))

[IRegionViewRegistry Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionviewregistry_members(v=pandp.50))

[RegisterViewWithRegion Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionviewregistry.registerviewwithregion(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
