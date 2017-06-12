---
TOCTitle: MefRegionNavigationJournal Class
Title: 'MefRegionNavigationJournal Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationJournal'
ms:mtpsurl: 'mefregionnavigationjournal-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationJournal Class

Exports the MefRegionNavigationJournal using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionNavigationJournal : RegionNavigationJournal
```

```VB
'Declaration
Public Class MefRegionNavigationJournal
	Inherits RegionNavigationJournal
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionNavigationJournal](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationJournal

## See Also

[MefRegionNavigationJournal Members](/patterns-practices/reference/mefregionnavigationjournal-members-mspp-mefextensions-regions)<br/>
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)