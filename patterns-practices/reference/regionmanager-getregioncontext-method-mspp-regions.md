---
TOCTitle: GetRegionContext Method
Title: 'RegionManager.GetRegionContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionContext(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getregioncontext-method-mspp-regions.md'
---

# RegionManager.GetRegionContext Method

Gets the value of the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static Object GetRegionContext(
	DependencyObject target
)
```

```VB
'Declaration
Public Shared Function GetRegionContext ( 
	target As DependencyObject
) As Object
```

### Parameters

*target*  
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
The target element.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The region context to pass to the contained views.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)  
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  