---
TOCTitle: GetRegionManager Method
Title: 'RegionManager.GetRegionManager Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionManager(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getregionmanager-method-mspp-regions.md'
---


# RegionManager.GetRegionManager Method

Gets the value of the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static IRegionManager GetRegionManager(
	DependencyObject target
)
```
```VB
'Declaration
Public Shared Function GetRegionManager ( 
	target As DependencyObject
) As IRegionManager
```

### Parameters

*target*

Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)

The target element.

### Return Value

Type: [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)

The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) attached to the *target* element.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)<br/>
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>