---
TOCTitle: Add Method
Title: 'RegionBehaviorCollection.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.Add(System.String,Microsoft.Practices.Prism.Regions.IRegionBehavior)'
ms:mtpsurl: 'regionbehaviorcollection-add-method-mspp-regions.md'
---


# RegionBehaviorCollection.Add Method

Adds a [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) to the collection, using the specified key as an indexer.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void Add(
	string key,
	IRegionBehavior regionBehavior
)
```
```VB
'Declaration
Public Sub Add ( 
	key As String,
	regionBehavior As IRegionBehavior
)
```

### Parameters

_key_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The key that specifies the type of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) that's added.

_regionBehavior_  
Type: [Microsoft.Practices.Prism.Regions.IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)  
The [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) to add.

### Implements

[IRegionBehaviorCollection.Add(String, IRegionBehavior)](/patterns-practices/reference/iregionbehaviorcollection-add-method-mspp-regions)

## Exceptions


| Exception                                                                             | Condition                                                                        |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | Thrown is the _key_ parameter is Null, or if the _regionBehavior_ parameter is Null. |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | Thrown if a behavior with the specified Key parameter already exists.            |

## See Also

[RegionBehaviorCollection Class](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)<br/>
[RegionBehaviorCollection Members](/patterns-practices/reference/regionbehaviorcollection-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>