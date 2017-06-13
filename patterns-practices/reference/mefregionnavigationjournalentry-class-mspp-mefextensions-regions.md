---
TOCTitle: MefRegionNavigationJournalEntry Class
Title: 'MefRegionNavigationJournalEntry Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationJournalEntry'
ms:mtpsurl: 'mefregionnavigationjournalentry-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationJournalEntry Class

Exports the RegionNavigationJournalEntry using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll) Version: 5.0.0.0 (5.0.0.0)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```c#
public class MefRegionNavigationJournalEntry : RegionNavigationJournalEntry
```

```VB
'Declaration
Public Class MefRegionNavigationJournalEntry
	Inherits RegionNavigationJournalEntry
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionNavigationJournalEntry](/patterns-practices/reference/regionnavigationjournalentry-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationJournalEntry

## See Also

[MefRegionNavigationJournalEntry Members](/patterns-practices/reference/mefregionnavigationjournalentry-members-mspp-mefextensions-regions)<br/>
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)