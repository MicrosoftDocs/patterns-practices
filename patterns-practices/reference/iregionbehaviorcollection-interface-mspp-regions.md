---
TOCTitle: IRegionBehaviorCollection Interface
Title: 'IRegionBehaviorCollection Interface (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.IRegionBehaviorCollection'
ms:mtpsurl: 'iregionbehaviorcollection-interface-mspp-regions.md'
---

# IRegionBehaviorCollection Interface

Defines the interface for a collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) classes on a Region.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public interface IRegionBehaviorCollection : IEnumerable<KeyValuePair<string, IRegionBehavior>>, 
	IEnumerable
```

```VB
'Declaration
Public Interface IRegionBehaviorCollection
	Inherits IEnumerable(Of KeyValuePair(Of String, IRegionBehavior)), 
	IEnumerable
```

## See Also

[IRegionBehaviorCollection Members](/patterns-practices/reference/iregionbehaviorcollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
