---
TOCTitle: GetRegionName Method
Title: 'RegionManager.GetRegionName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManager.GetRegionName(System.Windows.DependencyObject)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418964(v=PandP.50)'
---

# RegionManager.GetRegionName Method

Gets the value for the [RegionNameProperty](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager.regionnameproperty(v=pandp.50)) attached property.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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

    Type: [System.Windows.DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309)<br/>
    The object to adapt. This is typically a container (i.e a control).

### Return Value

Type: [String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)<br/>
The name of the region that should be created when [RegionManagerProperty](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager.regionmanagerproperty(v=pandp.50)) is also set in this element.

## See Also

[RegionManager Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager(v=pandp.50))

[RegionManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))