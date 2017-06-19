---
TOCTitle: RegionActiveAwareBehavior Class
Title: 'RegionActiveAwareBehavior Class (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Behaviors.RegionActiveAwareBehavior'
ms:mtpsurl: 'regionactiveawarebehavior-class-mspp-regions-behaviors.md'
---


# RegionActiveAwareBehavior Class

Behavior that monitors a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) object and changes the value for the [IsActive](/patterns-practices/reference/iactiveaware-isactive-property-mspp) property when an object that implements [IActiveAware](/patterns-practices/reference/iactiveaware-interface-mspp) gets added or removed from the collection.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class RegionActiveAwareBehavior : IRegionBehavior
```

```VB
'Declaration
Public Class RegionActiveAwareBehavior
	Implements IRegionBehavior
```

## Remarks

 This class can also sync the active state for any scoped regions directly on the view based on the [SyncActiveStateAttribute](/patterns-practices/reference/syncactivestateattribute-class-mspp-regions). If you use the [Add(Object, String, Boolean)](/patterns-practices/reference/region-add-method-object-string-boolean-mspp-regions) method with the createRegionManagerScope option, the scoped manager will be attached to the view.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Regions.Behaviors.RegionActiveAwareBehavior  
    [Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionActiveAwareBehavior](/patterns-practices/reference/mefregionactiveawarebehavior-class-mspp-mefextensions-regions-behaviors)

## See Also

[RegionActiveAwareBehavior Members](/patterns-practices/reference/regionactiveawarebehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
