---
TOCTitle: GetContents Method
Title: 'IRegionViewRegistry.GetContents Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.GetContents(System.String)'
ms:mtpsurl: 'iregionviewregistry-getcontents-method-mspp-regions.md'
---


# IRegionViewRegistry.GetContents Method

Returns the contents associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IEnumerable<Object> GetContents(
	string regionName
)
```

### Parameters

*regionName*
  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Region name for which contents are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

Collection of contents associated with the *regionName*.


```VB
'Declaration
Function GetContents ( 
	regionName As String
) As IEnumerable(Of Object)
```

### Parameters

*regionName*
  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Region name for which contents are requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

Collection of contents associated with the *regionName*.

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)  
[IRegionViewRegistry Members](/patterns-practices/reference/iregionviewregistry-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  