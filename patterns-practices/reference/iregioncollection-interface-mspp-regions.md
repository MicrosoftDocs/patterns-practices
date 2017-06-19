---
TOCTitle: IRegionCollection Interface
Title: 'IRegionCollection Interface (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.IRegionCollection'
ms:mtpsurl: 'iregioncollection-interface-mspp-regions.md'
---

# IRegionCollection Interface

Defines a collection of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)
 uniquely identified by their Name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public interface IRegionCollection : IEnumerable<IRegion>, 
	IEnumerable, INotifyCollectionChanged
```

```VB
'Declaration
Public Interface IRegionCollection
	Inherits IEnumerable(Of IRegion), IEnumerable, INotifyCollectionChanged
```
## See Also

[IRegionCollection Members](/patterns-practices/reference/iregioncollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
