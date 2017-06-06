---
TOCTitle: GetContents Method
Title: 'IRegionViewRegistry.GetContents Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.GetContents(System.String)'
ms:mtpsurl: 'iregionviewregistry-getcontents-method-mspp-regions.md'
---


# IRegionViewRegistry.GetContents Method

Returns the contents associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IEnumerable<Object> GetContents(
	string regionName
)
```

### Parameters

*regionName*<br/>  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
Region name for which contents are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;<br/>
Collection of contents associated with the *regionName*.


```VB
'Declaration
Function GetContents ( 
	regionName As String
) As IEnumerable(Of Object)
```

### Parameters

*regionName*<br/>  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
Region name for which contents are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))<br/>
Collection of contents associated with the *regionName*.

## See Also

[IRegionViewRegistry Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry)

[IRegionViewRegistry Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionviewregistry_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
