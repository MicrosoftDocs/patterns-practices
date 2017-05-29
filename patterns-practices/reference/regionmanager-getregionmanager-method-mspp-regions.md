---
TOCTitle: GetRegionManager Method
Title: 'RegionManager.GetRegionManager Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionManager(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getregionmanager-method-mspp-regions.md'
---

# RegionManager.GetRegionManager Method

Gets the value of the [RegionNameProperty](regionmanager-regionnameproperty-field-mspp-regions.md) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

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

Type: [IRegionManager](iregionmanager-interface-mspp-regions.md)

The [IRegionManager](iregionmanager-interface-mspp-regions.md) attached to the target element.

## See Also
[RegionManager Class](regionmanager-class-mspp-regions.md)

[RegionManager Members](regionmanager-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
