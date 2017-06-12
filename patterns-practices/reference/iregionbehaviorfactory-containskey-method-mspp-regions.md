---
TOCTitle: ContainsKey Method
Title: 'IRegionBehaviorFactory.ContainsKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory.ContainsKey(System.String)'
ms:mtpsurl: 'iregionbehaviorfactory-containskey-method-mspp-regions.md'
---

# IRegionBehaviorFactory.ContainsKey Method

Determines whether a behavior with the specified key already exists

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool ContainsKey(
	string behaviorKey
)
```

```VB
'Declaration
Function ContainsKey ( 
	behaviorKey As String
) As Boolean
```

### Parameters

*behaviorKey*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The behavior key.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if a behavior with the specified key is present; otherwise, **falsefalse** (**False** in Visual Basic).

## See Also

[IRegionBehaviorFactory Interface](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)<br/>
[IRegionBehaviorFactory Members](/patterns-practices/reference/iregionbehaviorfactory-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>