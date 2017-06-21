---
TOCTitle: GetMapping Method
Title: 'RegionAdapterMappings.GetMapping Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterMappings.GetMapping(System.Type)'
ms:mtpsurl: 'regionadaptermappings-getmapping-method-mspp-regions.md'
---


# RegionAdapterMappings.GetMapping Method

Returns the adapter associated with the type provided.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IRegionAdapter GetMapping(
	Type controlType
)
```

```VB
'Declaration
Public Function GetMapping ( 
	controlType As Type
) As IRegionAdapter
```

### Parameters

*controlType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The type to obtain the [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) mapped.

### Return Value

Type: [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)  
The [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) mapped to the *controlType*.

## Remarks

This class will look for a registered type for *controlType* and if there is not any, it will look for a registered type for any of its ancestors in the class hierarchy. If there is no registered type for *controlType* or any of its ancestors, an exception will be thrown.

## Exceptions


| Exception                                                                                                | Condition                                                                 |
|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| [System.Collections.Generic.KeyNotFoundException](http://msdn.microsoft.com/en-us/library/9a35cy81) | When there is no registered type for *controlType* or any of its ancestors. |

## See Also

[RegionAdapterMappings Class](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)  
[RegionAdapterMappings Members](/patterns-practices/reference/regionadaptermappings-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  