---
TOCTitle: SyncRegionContextWithHostBehavior Class
Title: 'SyncRegionContextWithHostBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior'
ms:mtpsurl: 'syncregioncontextwithhostbehavior-class-mspp-regions-behaviors.md'
---


# SyncRegionContextWithHostBehavior Class

Behavior that synchronizes the [Context](/patterns-practices/reference/iregion-context-property-mspp-regions) property of a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) with the control that hosts the Region. It does this by setting the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class SyncRegionContextWithHostBehavior : RegionBehavior, 
	IHostAwareRegionBehavior, IRegionBehavior
```

```VB
'Declaration
Public Class SyncRegionContextWithHostBehavior
	Inherits RegionBehavior
	Implements IHostAwareRegionBehavior, IRegionBehavior
```

### Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)  
    Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior  
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSyncRegionContextWithHostBehavior](/patterns-practices/reference/mefsyncregioncontextwithhostbehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[SyncRegionContextWithHostBehavior Members](/patterns-practices/reference/syncregioncontextwithhostbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
