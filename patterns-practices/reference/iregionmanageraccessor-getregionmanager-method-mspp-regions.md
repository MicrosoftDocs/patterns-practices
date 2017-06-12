---
TOCTitle: GetRegionManager Method
Title: 'IRegionManagerAccessor.GetRegionManager Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.GetRegionManager(System.Windows.DependencyObject)'
ms:mtpsurl: 'iregionmanageraccessor-getregionmanager-method-mspp-regions.md'
---

# IRegionManagerAccessor.GetRegionManager Method

Gets the value of the RegionName attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegionManager GetRegionManager(
	DependencyObject element
)
```

```VB
'Declaration
Function GetRegionManager ( 
	element As DependencyObject
) As IRegionManager
```

### Parameters

*element*

Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)

The target element.

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)

The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) attached to the element element.

## See Also

[IRegionManagerAccessor Interface](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)

[IRegionManagerAccessor Members](/patterns-practices/reference/iregionmanageraccessor-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
