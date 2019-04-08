---
TOCTitle: RegionBehaviorFactory Class
Title: 'RegionBehaviorFactory Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory'
ms:mtpsurl: 'regionbehaviorfactory-class-mspp-regions.md'
---

# RegionBehaviorFactory Class

Defines a factory that allows the registration of the default set of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions), that will be added to the [IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions) of all [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)s, unless overridden on a 'per-region' basis.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public class RegionBehaviorFactory : IRegionBehaviorFactory, 
	IEnumerable<string>, IEnumerable
```

```VB
'Declaration
Public Class RegionBehaviorFactory
	Implements IRegionBehaviorFactory, IEnumerable(Of String), 
	IEnumerable
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Regions.RegionBehaviorFactory  
    [Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionBehaviorFactory](/patterns-practices/reference/mefregionbehaviorfactory-class-mspp-mefextensions-regions)

## See Also

[RegionBehaviorFactory Members](/patterns-practices/reference/regionbehaviorfactory-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  