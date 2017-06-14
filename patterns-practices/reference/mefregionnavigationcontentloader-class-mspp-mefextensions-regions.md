---
TOCTitle: MefRegionNavigationContentLoader Class
Title: 'MefRegionNavigationContentLoader Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader'
ms:mtpsurl: 'mefregionnavigationcontentloader-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationContentLoader Class

Exports the LocatorNavigationTargetHandler using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionNavigationContentLoader : RegionNavigationContentLoader
```

```VB
'Declaration
Public Class MefRegionNavigationContentLoader
	Inherits RegionNavigationContentLoader
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader](/patterns-practices/reference/regionnavigationcontentloader-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoade

## See Also

[MefRegionNavigationContentLoader Members](/patterns-practices/reference/mefregionnavigationcontentloader-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)