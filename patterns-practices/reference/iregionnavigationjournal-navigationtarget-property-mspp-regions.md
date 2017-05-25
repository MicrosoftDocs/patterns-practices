---
TOCTitle: NavigationTarget Property
Title: 'IRegionNavigationJournal.NavigationTarget Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal.NavigationTarget'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431345(v=PandP.50)'
---


# IRegionNavigationJournal.NavigationTarget Property

Gets or sets the target that implements INavigateAsync.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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

Type: [INavigateAsync](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigateasync(v=pandp.50))
The INavigate implementation.

## Remarks

 This is set by the owner of this journal.

## See Also

[IRegionNavigationJournal Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal(v=pandp.50))

[IRegionNavigationJournal Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
