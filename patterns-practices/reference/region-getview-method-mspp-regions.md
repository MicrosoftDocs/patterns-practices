---
TOCTitle: GetView Method
Title: 'Region.GetView Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.GetView(System.String)'
ms:mtpsurl: 'region-getview-method-mspp-regions.md'
---


# Region.GetView Method

Returns the view instance that was added to the region using a specific name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public virtual Object GetView(
	string viewName
)
```
```VB
'Declaration
Public Overridable Function GetView ( 
	viewName As String
) As Object
```

### Parameters

*viewName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name used when adding the view to the region.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
Returns the named view or nullNothingnullptra null reference (Nothing in Visual Basic) if the view with viewName does not exist in the current region.
### Implements

[IRegion.GetView(String)](/patterns-practices/reference/iregion-getview-method-mspp-regions)

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)

[Region Members](/patterns-practices/reference/region-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)