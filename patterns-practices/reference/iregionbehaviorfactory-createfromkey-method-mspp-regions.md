---
TOCTitle: CreateFromKey Method
Title: 'IRegionBehaviorFactory.CreateFromKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory.CreateFromKey(System.String)'
ms:mtpsurl: 'iregionbehaviorfactory-createfromkey-method-mspp-regions.md'
---

# IRegionBehaviorFactory.CreateFromKey Method

Creates an instance of the Behaviortype that's registered using the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegionBehavior CreateFromKey(
	string key
)
```

```VB
'Declaration
Function CreateFromKey ( 
	key As String
) As IRegionBehavior
```

### Parameters

*key*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The key that's used to register a behavior type.

### Return Value

Type: [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)

The created behavior.

## See Also

[IRegionBehaviorFactory Interface](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)<br/>
[IRegionBehaviorFactory Members](/patterns-practices/reference/iregionbehaviorfactory-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>