---
TOCTitle: AddIfMissing Method
Title: 'RegionBehaviorFactory.AddIfMissing Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory.AddIfMissing(System.String,System.Type)'
ms:mtpsurl: 'regionbehaviorfactory-addifmissing-method-mspp-regions.md'
---


# RegionBehaviorFactory.AddIfMissing Method

Adds a particular type of RegionBehavior if it was not already registered. The behaviorKey string is used to check if the behavior is already present

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

~~~C#
public void AddIfMissing(
	string behaviorKey,
	Type behaviorType
)
~~~
~~~VB
'Declaration
Public Sub AddIfMissing ( 
	behaviorKey As String,
	behaviorType As Type
)
~~~
### Parameters

_behaviorKey_  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The behavior key that's used to find if a certain behavior is already added.

_behaviorType_  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Type of the behavior to add.

### Implements

[IRegionBehaviorFactory.AddIfMissing(String, Type)](/patterns-practices/reference/iregionbehaviorfactory-addifmissing-method-mspp-regions)

## See Also

[RegionBehaviorFactory Class](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)<br/>
[RegionBehaviorFactory Members](/patterns-practices/reference/regionbehaviorfactory-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>