---
TOCTitle: GetRegionName Method
Title: 'RegionManager.GetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionName(System.Windows.DependencyObject)'
ms:mtpsurl: 'regionmanager-getregionname-method-mspp-regions.md'
---

# RegionManager.GetRegionName Method

Gets the value for the [RegionNameProperty](regionmanager-regionnameproperty-field-mspp-regions.md) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static string GetRegionName(
	DependencyObject regionTarget
)
```

```VB
'Declaration
Public Shared Function GetRegionName ( 
	regionTarget As DependencyObject
) As String
```
### Parameters

*regionTarget*

    Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)<br/>
    The object to adapt. This is typically a container (i.e a control).

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the region that should be created when [RegionManagerProperty](regionmanager-regionmanagerproperty-field-mspp-regions.md) is also set in this element.

## See Also

[RegionManager Class](regionmanager-class-mspp-regions.md)

[RegionManager Members](regionmanager-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)