---
TOCTitle: SyncRegionContextWithHostBehavior Class
Title: 'SyncRegionContextWithHostBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431520(v=PandP.50)'
---

Prism Class Library

# SyncRegionContextWithHostBehavior Class

Behavior that synchronizes the [Context](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion.context(v=pandp.50)) property of a [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) with the control that hosts the Region. It does this by setting the [RegionContextProperty](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager.regioncontextproperty(v=pandp.50)) Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

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

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)

  [Microsoft.Practices.Prism.Regions.RegionBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionbehavior(v=pandp.50))
    Microsoft.Practices.Prism.Regions.Behaviors.SyncRegionContextWithHostBehavior
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefSyncRegionContextWithHostBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefsyncregioncontextwithhostbehavior(v=pandp.50))

## See Also

<span id="seeAlsoToggle"></span>
[SyncRegionContextWithHostBehavior Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))
