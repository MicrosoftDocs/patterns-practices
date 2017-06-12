---
TOCTitle: CreateFromKey Method
Title: 'RegionBehaviorFactory.CreateFromKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionBehaviorFactory.CreateFromKey(System.String)'
ms:mtpsurl: 'regionbehaviorfactory-createfromkey-method-mspp-regions.md'
---


# RegionBehaviorFactory.CreateFromKey Method

Creates an instance of the behavior [Type](http://msdn.microsoft.com/en-us/library/42892f65) that is registered using the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IRegionBehavior CreateFromKey(
	string key
)
```

```VB
'Declaration
Public Function CreateFromKey ( 
	key As String
) 
```

### Parameters

*key*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The key that is used to register a behavior type.

### Return Value

Type: [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)  
A new instance of the behavior.

### Implements

[IRegionBehaviorFactory.CreateFromKey(String)](/patterns-practices/reference/iregionbehaviorfactory-createfromkey-method-mspp-regions)

## See Also

[RegionBehaviorFactory Class](/patterns-practices/reference/regionbehaviorfactory-class-mspp-regions)

[RegionBehaviorFactory Members](/patterns-practices/reference/regionbehaviorfactory-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
