---
TOCTitle: RegionBehaviorCollection Class
Title: 'RegionBehaviorCollection Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection'
ms:mtpsurl: 'regionbehaviorcollection-class-mspp-regions.md'
---

# RegionBehaviorCollection Class

A collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) instances, that are stored and retrieved by Key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public class RegionBehaviorCollection : IRegionBehaviorCollection, 
	IEnumerable<KeyValuePair<string, IRegionBehavior>>, IEnumerable
```

```VB
'Declaration
Public Class RegionBehaviorCollection
	Implements IRegionBehaviorCollection, IEnumerable(Of KeyValuePair(Of String, IRegionBehavior)), 
	IEnumerable
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Regions.RegionBehaviorCollection

## See Also

[RegionBehaviorCollection Members](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
