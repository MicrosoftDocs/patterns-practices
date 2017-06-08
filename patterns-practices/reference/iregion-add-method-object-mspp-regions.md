---
TOCTitle: 'Add Method (Object)'
Title: 'IRegion.Add Method (Object) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegion.Add(System.Object)'
ms:mtpsurl: 'iregion-add-method-mspp-regions.md'
---

# IRegion.Add Method (Object)

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegionManager Add(
	Object view
)
```

```VB
'Declaration
Function Add ( 
	view As Object
) As IRegionManager
```

### Parameters

*view*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
The view to add.

### Return Value

Type: [IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50))<br/>
The [IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50)) that is set on the view if it is a [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309). It will be the current region manager when using this overload.

## See Also

[IRegion Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50))

[IRegion Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion_members(v=pandp.50))

[Add Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion.add(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
