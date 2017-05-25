---
TOCTitle: CreateFromKey Method
Title: 'RegionBehaviorFactory.CreateFromKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory.CreateFromKey(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418946(v=PandP.50)'
---

Prism Class Library

RegionBehaviorFactory.CreateFromKey Method
==============================================

Creates an instance of the behavior [Type](http://msdn.microsoft.com/en-us/library/42892f65) that is registered using the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public IRegionBehavior CreateFromKey( string key )Public Function CreateFromKey ( key As String ) As IRegionBehavior

### Parameters

key  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The key that is used to register a behavior type.

### Return Value

Type: [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior)
A new instance of the behavior.
### Implements

[IRegionBehaviorFactory.CreateFromKey(String)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory.createfromkey(system.string))

See Also
--------


[RegionBehaviorFactory Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehaviorfactory)

[RegionBehaviorFactory Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionbehaviorfactory)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
