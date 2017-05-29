---
TOCTitle: SyncRegionContextWithHostBehavior Class
Title: 'SyncRegionContextWithHostBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior'
ms:mtpsurl: 'syncregioncontextwithhostbehavior-class-mspp-regions-behaviors.md'
---

# SyncRegionContextWithHostBehavior Class

Behavior that synchronizes the [Context](iregion-context-property-mspp-regions.md) property of a [IRegion](iregion-interface-mspp-regions.md) with the control that hosts the Region. It does this by setting the [RegionContextProperty](regionmanager-regioncontextproperty-field-mspp-regions.md) Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](mspp-regions-behaviors-namespace.md)

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

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  [Microsoft.Practices.Prism.Regions.RegionBehavior](regionbehavior-class-mspp-regions.md)
    Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSyncRegionContextWithHostBehavior](mefsyncregioncontextwithhostbehavior-class-mspp-mefextensions-regions-behaviors.md)

## See Also
[SyncRegionContextWithHostBehavior Members](syncregioncontextwithhostbehavior-members-mspp-regions-behaviors.md)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](mspp-regions-behaviors-namespace.md)
