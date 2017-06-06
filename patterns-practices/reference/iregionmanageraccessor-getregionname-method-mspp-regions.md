---
TOCTitle: GetRegionName Method
Title: 'IRegionManagerAccessor.GetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.GetRegionName(System.Windows.DependencyObject)'
ms:mtpsurl: 'iregionmanageraccessor-getregionname-method-mspp-regions.md'
---

# IRegionManagerAccessor.GetRegionName Method

Gets the value for the RegionName attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
string GetRegionName(
	DependencyObject element
)
```

```VB
'Declaration
Function GetRegionName ( 
	element As DependencyObject
) As String
```

### Parameters

*element*  
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)<br/>
The object to adapt. This is typically a container (i.e a control).

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the region that should be created when the RegionManager is also set in this element.

## See Also

[IRegionManagerAccessor Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanageraccessor)

[IRegionManagerAccessor Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanageraccessor_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
