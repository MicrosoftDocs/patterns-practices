---
TOCTitle: CreateRegion Method
Title: 'DelayedRegionCreationBehavior.CreateRegion Method (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior.CreateRegion(System.Windows.DependencyObject,System.String)'
ms:mtpsurl: 'delayedregioncreationbehavior-createregion-method-mspp-regions-behaviors.md'
---

# DelayedRegionCreationBehavior.CreateRegion Method

Method that will create the region, by calling the right [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions.Behaviors](/patterns-practices/reference/mspp-regions-behaviors-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual IRegion CreateRegion(
	DependencyObject targetElement,
	string regionName
)
```

```VB
'Declaration
Protected Overridable Function CreateRegion ( 
	targetElement As DependencyObject,
	regionName As String
) As IRegion
```
### Parameters

*targetElement*  
Type: [System.Windows.DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309)  
The target element that will host the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the region.

### Return Value

Type: [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The created [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)  
[DelayedRegionCreationBehavior Members](/patterns-practices/reference/delayedregioncreationbehavior-members-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  