---
TOCTitle: CreateFromKey Method
Title: 'IRegionBehaviorFactory.CreateFromKey Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory.CreateFromKey(System.String)'
ms:mtpsurl: 'iregionbehaviorfactory-createfromkey-method-mspp-regions.md'
---

# IRegionBehaviorFactory.CreateFromKey Method

Creates an instance of the Behaviortype that's registered using the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)

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

*key*<br/>
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The key that's used to register a behavior type.

### Return Value

Type: [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior)<br/>
The created behavior.

## See Also

[IRegionBehaviorFactory Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehaviorfactory)

[IRegionBehaviorFactory Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionbehaviorfactory_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
