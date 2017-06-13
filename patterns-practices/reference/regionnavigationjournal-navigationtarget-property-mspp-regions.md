---
TOCTitle: NavigationTarget Property
Title: 'RegionNavigationJournal.NavigationTarget Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.RegionNavigationJournal.NavigationTarget'
ms:mtpsurl: 'regionnavigationjournal-navigationtarget-property-mspp-regions.md'
---


# RegionNavigationJournal.NavigationTarget Property

Gets or sets the target that implements INavigate.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public INavigateAsync NavigationTarget { get; set; }
```
```VB
'Declaration
Public Property NavigationTarget As INavigateAsync
	Get
	Set
```
### Property Value

Type: [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)  
The INavigate implementation.  
### Implements

[IRegionNavigationJournal.NavigationTarget](/patterns-practices/reference/iregionnavigationjournal-navigationtarget-property-mspp-regions)

## Remarks

 This is set by the owner of this journal.

## See Also

[RegionNavigationJournal Class](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions)<br/>
[RegionNavigationJournal Members](/patterns-practices/reference/regionnavigationjournal-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>