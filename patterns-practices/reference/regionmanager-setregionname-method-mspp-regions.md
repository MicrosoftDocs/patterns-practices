---
TOCTitle: SetRegionName Method
Title: 'RegionManager.SetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.SetRegionName(System.Windows.DependencyObject,System.String)'
ms:mtpsurl: 'regionmanager-setregionname-method-mspp-regions.md'
---
# RegionManager.SetRegionName Method

Sets the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public static void SetRegionName(
	DependencyObject regionTarget,
	string regionName
)
```

```VB
'Declaration
Public Shared Sub SetRegionName ( 
	regionTarget As DependencyObject,
	regionName As String
)
```

### Parameters

*regionTarget*  
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
The object to adapt. This is typically a container (i.e a control).

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the region to register.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)  
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

