---
TOCTitle: NavigationTarget Property
Title: 'IRegionNavigationJournal.NavigationTarget Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal.NavigationTarget'
ms:mtpsurl: 'iregionnavigationjournal-navigationtarget-property-mspp-regions.md'
---

# IRegionNavigationJournal.NavigationTarget Property

Gets or sets the target that implements INavigateAsync.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
INavigateAsync NavigationTarget { get; set; }
```
```VB
'Declaration
Property NavigationTarget As INavigateAsync
	Get
	Set
```

### Property Value

Type: [INavigateAsync](inavigateasync-interface-mspp-regions)
The INavigate implementation.

## Remarks

 This is set by the owner of this journal.

## See Also
[IRegionNavigationJournal Interface](iregionnavigationjournal-interface-mspp-regions)

[IRegionNavigationJournal Members](iregionnavigationjournal-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace)
