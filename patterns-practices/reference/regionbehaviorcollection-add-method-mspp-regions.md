---
TOCTitle: Add Method
Title: 'RegionBehaviorCollection.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.Add(System.String,Microsoft.Practices.Prism.Regions.IRegionBehavior)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418940(v=PandP.50)'
---

Prism Class Library

RegionBehaviorCollection.Add Method
=======================================

Adds a [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior) to the collection, using the specified key as an indexer.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void Add( string key, IRegionBehavior regionBehavior )Public Sub Add ( key As String, regionBehavior As IRegionBehavior )
#### Parameters

key  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The key that specifies the type of [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior) that's added.

regionBehavior  
Type: [Microsoft.Practices.Prism.Regions.IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior)
The [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior) to add.

#### Implements

[IRegionBehaviorCollection.Add(String, IRegionBehavior)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionbehaviorcollection.add(system.string%2cmicrosoft.practices.prism.regions.iregionbehavior))

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                        |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | Thrown is the key parameter is Null, or if the regionBehavior parameter is Null. |
| [System.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114)     | Thrown if a behavior with the specified Key parameter already exists.            |

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionBehaviorCollection Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehaviorcollection)

[RegionBehaviorCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionbehaviorcollection)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
