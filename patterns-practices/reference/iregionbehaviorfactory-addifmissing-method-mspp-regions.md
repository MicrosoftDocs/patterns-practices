---
TOCTitle: AddIfMissing Method
Title: 'IRegionBehaviorFactory.AddIfMissing Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory.AddIfMissing(System.String,System.Type)'
ms:mtpsurl: 'iregionbehaviorfactory-addifmissing-method-mspp-regions.md'
---

# IRegionBehaviorFactory.AddIfMissing Method

Adds a particular type of RegionBehavior if it was not already registered. the behaviorKey string is used to check if the behavior is already present

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
void AddIfMissing(
	string behaviorKey,
	Type behaviorType
)
```

```VB
'Declaration
Sub AddIfMissing ( 
	behaviorKey As String,
	behaviorType As Type
)
```


### Parameters

*behaviorKey*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The behavior key that's used to find if a certain behavior is already added.

*behaviorType*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type of the behavior to add.

## See Also

[IRegionBehaviorFactory Interface](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)  
[IRegionBehaviorFactory Members](/patterns-practices/reference/iregionbehaviorfactory-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  