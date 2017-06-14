---
TOCTitle: 'Add Method (Object)'
Title: 'Region.Add Method (Object) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.Add(System.Object)'
ms:mtpsurl: 'region-add-method-mspp-regions.md'
---
# Region.Add Method (Object)

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public IRegionManager Add(
	Object view
)
```

```VB
'Declaration
Public Function Add ( 
	view As Object
) As IRegionManager
```

### Parameters

*view*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The view to add.

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that is set on the view if it is a [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309). It will be the current region manager when using this overload.
### Implements

[IRegion.Add(Object)](/patterns-practices/reference/iregion-add-method-object-mspp-regions)

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)  
[Region Members](/patterns-practices/reference/region-members-mspp-regions)  
[Add Overload](/patterns-practices/reference/region-add-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

