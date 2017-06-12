---
TOCTitle: ContainsKey Method
Title: 'RegionBehaviorFactory.ContainsKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory.ContainsKey(System.String)'
ms:mtpsurl: 'regionbehaviorfactory-containskey-method-mspp-regions.md'
---


# RegionBehaviorFactory.ContainsKey Method

Determines whether a behavior with the specified key already exists.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool ContainsKey(
	string behaviorKey
)
```

```VB
'Declaration
Public Function ContainsKey ( 
	behaviorKey As String
) As Boolean
```

### Parameters

*behaviorKey*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The behavior key.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  

**truetrue** (**true** in Visual Basic) if a behavior with the specified key is present; otherwise, **Falsefalse** (**False** in Visual Basic).

### Implements

[IRegionBehaviorFactory.ContainsKey(String)](/patterns-practices/reference/iregionbehaviorfactory-containskey-method-mspp-regions)

## See Also

[RegionBehaviorFactory Class](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)

[RegionBehaviorFactory Members](/patterns-practices/reference/regionbehaviorfactory-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
