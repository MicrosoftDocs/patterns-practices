---
TOCTitle: OnAttach Method
Title: 'RegionManagerRegistrationBehavior.OnAttach Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior.OnAttach'
ms:mtpsurl: 'regionmanagerregistrationbehavior-onattach-method-mspp-regions-behaviors.md'
---

# RegionManagerRegistrationBehavior.OnAttach Method

When the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) has a name assigned, the behavior will start monitoring the ancestor controls in the element tree to look for an [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) where to register the region in.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected override void OnAttach()
```

```VB
'Declaration
Protected Overrides Sub OnAttach
```

## See Also

[RegionManagerRegistrationBehavior Class](/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors)  
[RegionManagerRegistrationBehavior Members](/patterns-practices/reference/regionmanagerregistrationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  