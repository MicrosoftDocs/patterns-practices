---
TOCTitle: RegisterMapping Method
Title: 'RegionAdapterMappings.RegisterMapping Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterMappings.RegisterMapping(System.Type,Microsoft.Practices.Prism.Regions.IRegionAdapter)'
ms:mtpsurl: 'regionadaptermappings-registermapping-method-mspp-regions.md'
---

Prism Class Library

RegionAdapterMappings.RegisterMapping Method
================================================

Registers the mapping between a type and an adapter.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public void RegisterMapping( Type controlType, IRegionAdapter adapter )Public Sub RegisterMapping ( controlType As Type, adapter As IRegionAdapter )

### Parameters

controlType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type of the control.

adapter  
Type: [Microsoft.Practices.Prism.Regions.IRegionAdapter](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionadapter)
The adapter to use with the controlType type.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                 | Condition                                                                                            |
|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)     | When any of controlType or adapter are nullNothingnullptra null reference (Nothing in Visual Basic). |
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | If a mapping for controlType already exists.                                                         |

See Also
--------


[RegionAdapterMappings Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadaptermappings)

[RegionAdapterMappings Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionadaptermappings)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
