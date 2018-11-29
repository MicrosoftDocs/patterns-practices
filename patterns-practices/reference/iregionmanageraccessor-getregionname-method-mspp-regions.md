---
TOCTitle: GetRegionName Method
Title: 'IRegionManagerAccessor.GetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.GetRegionName(System.Windows.DependencyObject)'
ms:mtpsurl: 'iregionmanageraccessor-getregionname-method-mspp-regions.md'
---

# IRegionManagerAccessor.GetRegionName Method

Gets the value for the RegionName attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
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
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
The object to adapt. This is typically a container (i.e a control).

### Return Value  
Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the region that should be created when the RegionManager is also set in this element.

## See Also

[IRegionManagerAccessor Interface](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)  
[IRegionManagerAccessor Members](/patterns-practices/reference/iregionmanageraccessor-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  