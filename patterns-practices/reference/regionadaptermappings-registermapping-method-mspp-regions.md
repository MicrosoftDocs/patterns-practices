---
TOCTitle: RegisterMapping Method
Title: 'RegionAdapterMappings.RegisterMapping Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterMappings.RegisterMapping(System.Type,Microsoft.Practices.Prism.Regions.IRegionAdapter)'
ms:mtpsurl: 'regionadaptermappings-registermapping-method-mspp-regions.md'
---


# RegionAdapterMappings.RegisterMapping Method

Registers the mapping between a type and an adapter.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RegisterMapping(
	Type controlType,
	IRegionAdapter adapter
)
```

### Parameters

*controlType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type of the control.

*adapter*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The adapter to use with the *controlType* type.

## Exceptions


| Exception                                                                                 | Condition                                                                                            |
|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)     | When any of *controlType* or *adapter* are **null**a null reference (**Nothing** in Visual Basic). |
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | If a mapping for *controlType* already exists.  

```VB
'Declaration
Public Sub RegisterMapping ( 
	controlType As Type,
	adapter As IRegionAdapter
)
```

### Parameters

*controlType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type of the control.

*adapter*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The adapter to use with the *controlType* type.

## Exceptions


| Exception                                                                                 | Condition                                                                                            |
|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)     | When any of *controlType* or *adapter* are **Nothing**a null reference (**Nothing** in Visual Basic). |
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | If a mapping for *controlType* already exists.                                                         |

## See Also

[RegionAdapterMappings Class](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)  
[RegionAdapterMappings Members](/patterns-practices/reference/regionadaptermappings-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  