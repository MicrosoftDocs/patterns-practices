---
TOCTitle: OnUpdatingRegions Method
Title: 'DelayedRegionCreationBehavior.OnUpdatingRegions Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.OnUpdatingRegions(System.Object,System.EventArgs)'
ms:mtpsurl: 'delayedregioncreationbehavior-onupdatingregions-method-mspp-regions-behaviors.md'
---


# DelayedRegionCreationBehavior.OnUpdatingRegions Method

Called when the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) is updating it's [Regions](/patterns-practices/reference/regionmanager-regions-property-mspp-regions) collection.

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void OnUpdatingRegions(
	Object sender,
	EventArgs e
)
```

```VB
'Declaration
Public Sub OnUpdatingRegions ( 
	sender As Object,
	e As EventArgs
)
```

### Parameters

*sender*  

Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

The [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions).

*e*  

Type: [System.EventArgs](http://msdn.microsoft.com/en-us/library/118wxtk3)

The [EventArgs](http://msdn.microsoft.com/en-us/library/118wxtk3) instance containing the event data.

## Remarks

This method has to be public, because it has to be callable using weak references in silverlight and other partial trust environments.

## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)

[DelayedRegionCreationBehavior Members](/patterns-practices/reference/delayedregioncreationbehavior-members-mspp-regions-behaviors)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)
