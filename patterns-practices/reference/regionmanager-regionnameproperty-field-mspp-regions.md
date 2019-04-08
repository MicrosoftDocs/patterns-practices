---
TOCTitle: RegionNameProperty Field
Title: 'RegionManager.RegionNameProperty Field (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'F:Microsoft.Practices.Prism.Regions.RegionManager.RegionNameProperty'
ms:mtpsurl: 'regionmanager-regionnameproperty-field-mspp-regions.md'
---

# RegionManager.RegionNameProperty Field

Identifies the RegionName attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static readonly DependencyProperty RegionNameProperty
```

### Field Value

Type: [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318)

## Remarks

When a control has both the RegionNameProperty and [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) attached properties set to a value different than **null**a null reference (**Nothing** in Visual Basic) and there is a [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) mapping registered for the control, it will create and adapt a new region for that control, and register it in the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) with the specified region name.

```VB
'Declaration
Public Shared ReadOnly RegionNameProperty As DependencyProperty
```

### Field Value

Type: [DependencyProperty](http://msdn.microsoft.com/en-us/library/ms589318)

## Remarks

When a control has both the RegionNameProperty and [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) attached properties set to a value different than **Nothing**a null reference (**Nothing** in Visual Basic) and there is a [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) mapping registered for the control, it will create and adapt a new region for that control, and register it in the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) with the specified region name.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)  
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)