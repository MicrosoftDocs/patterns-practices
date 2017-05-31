---
TOCTitle: RegionManagerRegistrationBehavior Class
Title: 'RegionManagerRegistrationBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior'
ms:mtpsurl: 'regionmanagerregistrationbehavior-class-mspp-regions-behaviors.md'
---

# RegionManagerRegistrationBehavior Class

Subscribes to a static event from the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) in order to register the target [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) in a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) property is not **null**a null reference (**Nothing** in Visual Basic).

Subscribes to a static event from the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) in order to register the target [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) in a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) property is not **Nothing**a null reference (**Nothing** in Visual Basic).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)

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
  [Microsoft.Practices.Prism.Regions.RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions)<br/>
    Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior<br/>
      [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionManagerRegistrationBehavior](/patterns-practices/reference/mefregionmanagerregistrationbehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[RegionManagerRegistrationBehavior Members](/patterns-practices/reference/regionmanagerregistrationbehavior-members-mspp-regions-behaviors)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)