---
TOCTitle: GetMapping Method
Title: 'RegionAdapterMappings.GetMapping Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterMappings.GetMapping(System.Type)'
ms:mtpsurl: 'regionadaptermappings-getmapping-method-mspp-regions.md'
---

# RegionAdapterMappings.GetMapping Method

Returns the adapter associated with the type provided.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
public IRegionAdapter GetMapping( Type controlType )Public Function GetMapping ( controlType As Type ) As IRegionAdapter

### Parameters

controlType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type to obtain the [IRegionAdapter](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter) mapped.

### Return Value

Type: [IRegionAdapter](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter)
The [IRegionAdapter](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter) mapped to the controlType.

## Remarks

This class will look for a registered type for controlType and if there is not any, it will look for a registered type for any of its ancestors in the class hierarchy. If there is no registered type for controlType or any of its ancestors, an exception will be thrown.

## Exceptions

<span id="exceptionsToggle"></span>
| Exception                                                                                                | Condition                                                                 |
|----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| [System.Collections.Generic.KeyNotFoundException](http://msdn.microsoft.com/en-us/library/9a35cy81) | When there is no registered type for controlType or any of its ancestors. |

## See Also
[RegionAdapterMappings Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadaptermappings)

[RegionAdapterMappings Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionadaptermappings)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
