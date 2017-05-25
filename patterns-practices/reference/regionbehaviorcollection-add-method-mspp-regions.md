---
TOCTitle: Add Method
Title: 'RegionBehaviorCollection.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.Add(System.String,Microsoft.Practices.Prism.Regions.IRegionBehavior)'
ms:mtpsurl: 'regionbehaviorcollection-add-method-mspp-regions.md'
---

Prism Class Library

RegionBehaviorCollection.Add Method
=======================================

Adds a [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior) to the collection, using the specified key as an indexer.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public void Add( string key, IRegionBehavior regionBehavior )Public Sub Add ( key As String, regionBehavior As IRegionBehavior )

### Parameters

key  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The key that specifies the type of [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior) that's added.

regionBehavior  
Type: [Microsoft.Practices.Prism.Regions.IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior)
The [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior) to add.

### Implements

[IRegionBehaviorCollection.Add(String, IRegionBehavior)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorcollection.add(system.string%2cmicrosoft.practices.prism.regions.iregionbehavior))

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                        |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown is the key parameter is Null, or if the regionBehavior parameter is Null. |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | Thrown if a behavior with the specified Key parameter already exists.            |

See Also
--------


[RegionBehaviorCollection Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehaviorcollection)

[RegionBehaviorCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionbehaviorcollection)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
