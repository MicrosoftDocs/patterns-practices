---
TOCTitle: 'Add Method (Object, String, Boolean)'
Title: 'IRegion.Add Method (Object, String, Boolean) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegion.Add(System.Object,System.String,System.Boolean)'
ms:mtpsurl: 'iregion-add-method-mspp-regions.md'
---

# IRegion.Add Method (Object, String, Boolean)

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegionManager Add(
	Object view,
	string viewName,
	bool createRegionManagerScope
)
```
```VB
'Declaration
Function Add ( 
	view As Object,
	viewName As String,
	createRegionManagerScope As Boolean
) As IRegionManager
```

### Parameters

*view*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The view to add.

*viewName*
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the view. This can be used to retrieve it later by calling [GetView(String)](/patterns-practices/reference/iregion-getview-method-mspp-regions).

*createRegionManagerScope*
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When **Truetrue** (True in Visual Basic), the added view will receive a new instance &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;of [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions), otherwise it will use the current region manager for this region.

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)

The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that is set on the view if it is a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309).

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)<br/>
[IRegion Members](/patterns-practices/reference/iregion-members-mspp-regions)<br/>
[Add Overload](/patterns-practices/reference/iregion-add-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>
