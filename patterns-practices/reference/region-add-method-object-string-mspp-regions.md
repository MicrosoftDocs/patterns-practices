---
TOCTitle: 'Add Method (Object, String)'
Title: 'Region.Add Method (Object, String) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.Add(System.Object,System.String)'
ms:mtpsurl: 'region-add-method-mspp-regions.md'
---


# Region.Add Method (Object, String)

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IRegionManager Add(
	Object view,
	string viewName
)
```

```VB
'Declaration
Public Function Add ( 
	view As Object,
	viewName As String
) As IRegionManager
```

### Parameters

*view*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The view to add.

*viewName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the view. This can be used to retrieve it later by calling [GetView(String)](/patterns-practices/reference/iregion-getview-method-mspp-regions).

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that is set on the view if it is a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309). It will be the current region manager when using this overload.
### Implements

[IRegion.Add(Object, String)](/patterns-practices/reference/iregion-add-method-object-string-mspp-regions)

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)  
[Region Members](/patterns-practices/reference/region-members-mspp-regions)  
[Add Overload](/patterns-practices/reference/region-add-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>