---
TOCTitle: GetView Method
Title: 'IRegion.GetView Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegion.GetView(System.String)'
ms:mtpsurl: 'iregion-getview-method-mspp-regions.md'
---

# IRegion.GetView Method

Returns the view instance that was added to the region using a specific name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
Object GetView(
	string viewName
)
```
```VB
'Declaration
Function GetView ( 
	viewName As String
) As Object
```

### Parameters

*viewName*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;he name used when adding the view to the region.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Returns the named view or **null**a null reference (**Nothing** in Visual Basic) if the view with viewName does not exist in the current region.

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[IRegion Members](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  