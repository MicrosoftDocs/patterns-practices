---
TOCTitle: MefSelectorItemsSourceSyncBehavior Class
Title: 'MefSelectorItemsSourceSyncBehavior Class (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSelectorItemsSourceSyncBehavior'
ms:mtpsurl: 'mefselectoritemssourcesyncbehavior-class-mspp-mefextensions-regions-behaviors.md'
---

# MefSelectorItemsSourceSyncBehavior Class

Exports the SelectorItemsSourceSyncBehavior using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefSelectorItemsSourceSyncBehavior : SelectorItemsSourceSyncBehavior
```

```VB
'Declaration
Public Class MefSelectorItemsSourceSyncBehavior
	Inherits SelectorItemsSourceSyncBehavior
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.Behaviors.SelectorItemsSourceSyncBehavior](/patterns-practices/reference/selectoritemssourcesyncbehavior-class-mspp-regions-behaviors)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSelectorItemsSourceSyncBehavior

## See Also

[MefSelectorItemsSourceSyncBehavior Members](/patterns-practices/reference/mefselectoritemssourcesyncbehavior-members-mspp-mefextensions-regions-behaviors)  
[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-mefextensions-regions-behaviors-namespace)