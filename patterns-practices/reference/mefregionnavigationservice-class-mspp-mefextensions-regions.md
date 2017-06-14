---
TOCTitle: MefRegionNavigationService Class
Title: 'MefRegionNavigationService Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationService'
ms:mtpsurl: 'mefregionnavigationservice-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationService Class

Exports the MefRegionNavigationService using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionNavigationService : RegionNavigationService
```

```VB
'Declaration
Public Class MefRegionNavigationService
	Inherits RegionNavigationService
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

[Microsoft.Practices.Prism.Regions.RegionNavigationService](/patterns-practices/reference/regionnavigationservice-class-mspp-regions)

Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationService

## See Also

[MefRegionNavigationService Members](/patterns-practices/reference/mefregionnavigationservice-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)