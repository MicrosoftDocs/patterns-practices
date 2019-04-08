---
TOCTitle: IRegionBehaviorFactory Interface
Title: 'IRegionBehaviorFactory Interface (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory'
ms:mtpsurl: 'iregionbehaviorfactory-interface-mspp-regions.md'
---

# IRegionBehaviorFactory Interface

Interface for RegionBehaviorFactories. This factory allows the registration of the default set of RegionBehaviors, that will be added to the [IRegionBehaviorCollection](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)s of all [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)s, unless overridden on a 'per-region' basis.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public interface IRegionBehaviorFactory : IEnumerable<string>, 
	IEnumerable
```

```VB
'Declaration
Public Interface IRegionBehaviorFactory
	Inherits IEnumerable(Of String), IEnumerable
```
## See Also

[IRegionBehaviorFactory Members](/patterns-practices/reference/iregionbehaviorfactory-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
