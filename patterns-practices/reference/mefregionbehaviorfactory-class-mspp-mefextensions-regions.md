---
TOCTitle: MefRegionBehaviorFactory Class
Title: 'MefRegionBehaviorFactory Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionBehaviorFactory'
ms:mtpsurl: 'mefregionbehaviorfactory-class-mspp-mefextensions-regions.md'
---


# MefRegionBehaviorFactory Class

Exports the RegionBehaviorFactory using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionBehaviorFactory : RegionBehaviorFactory
```

```VB
'Declaration
Public Class MefRegionBehaviorFactory
	Inherits RegionBehaviorFactory
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionBehaviorFactory](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionBehaviorFactory

## See Also

[MefRegionBehaviorFactory Members](/patterns-practices/reference/mefregionbehaviorfactory-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)