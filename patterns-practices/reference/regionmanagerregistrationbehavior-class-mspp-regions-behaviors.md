---
TOCTitle: RegionManagerRegistrationBehavior Class
Title: 'RegionManagerRegistrationBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior(v=pandp.50)'
---

# RegionManagerRegistrationBehavior Class

Subscribes to a static event from the [RegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager(v=pandp.50)) in order to register the target [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) in a [IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50)) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager.regionmanagerproperty(v=pandp.50)) property is not **null**a null reference (**Nothing** in Visual Basic).

Subscribes to a static event from the [RegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager(v=pandp.50)) in order to register the target [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) in a [IRegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanager(v=pandp.50)) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager.regionmanagerproperty(v=pandp.50)) property is not **Nothing**a null reference (**Nothing** in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class RegionManagerRegistrationBehavior : RegionBehavior,
	IHostAwareRegionBehavior, IRegionBehavior
```

```VB
'Declaration
Public Class RegionManagerRegistrationBehavior
	Inherits RegionBehavior
	Implements IHostAwareRegionBehavior, IRegionBehavior
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
  [Microsoft.Practices.Prism.Regions.RegionBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionbehavior(v=pandp.50))<br/>
    Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior<br/>
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior(v=pandp.50))

## See Also

[RegionManagerRegistrationBehavior Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors(v=pandp.50))