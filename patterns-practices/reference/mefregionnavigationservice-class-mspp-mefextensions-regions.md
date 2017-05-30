---
TOCTitle: MefRegionNavigationService Class
Title: 'MefRegionNavigationService Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationService'
ms:mtpsurl: 'mefregionnavigationservice-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationService Class

Exports the MefRegionNavigationService using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](mspp-mefextensions-regions-namespace)

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

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionNavigationService](regionnavigationservice-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationService

## See Also

[MefRegionNavigationService Members](mefregionnavigationservice-members-mspp-mefextensions-regions)

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](mspp-mefextensions-regions-namespace)