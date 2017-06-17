---
TOCTitle: GetContents Method
Title: 'RegionViewRegistry.GetContents Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.GetContents(System.String)'
ms:mtpsurl: 'regionviewregistry-getcontents-method-mspp-regions.md'
---

# RegionViewRegistry.GetContents Method

Returns the contents registered for a region.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IEnumerable<Object> GetContents(
	string regionName
)
```

### Parameters

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the region which content is being requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;  
Collection of contents registered for the region.

### Implements

[IRegionViewRegistry.GetContents(String)](/patterns-practices/reference/iregionviewregistry-getcontents-method-mspp-regions)


```VB
'Declaration
Public Function GetContents ( 
	regionName As String
) As IEnumerable(Of Object)
```

### Parameters

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the region which content is being requested.

### Return Value

Type: [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))  
Collection of contents registered for the region.

### Implements

[IRegionViewRegistry.GetContents(String)](/patterns-practices/reference/iregionviewregistry-getcontents-method-mspp-regions)

## See Also

[RegionViewRegistry Class](/patterns-practices/reference/regionviewregistry-class-mspp-regions)  
[RegionViewRegistry Members](/patterns-practices/reference/regionviewregistry-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  