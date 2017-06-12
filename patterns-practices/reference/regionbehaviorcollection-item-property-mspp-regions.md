---
TOCTitle: Item Property
Title: 'RegionBehaviorCollection.Item Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.RegionBehaviorCollection.Item(System.String)'
ms:mtpsurl: 'regionbehaviorcollection-item-property-mspp-regions.md'
---

# RegionBehaviorCollection.Item Property

Gets the [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) with the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public IRegionBehavior this[
	string key
] { get; }
```

```VB
'Declaration
Public ReadOnly Default Property Item ( 
	key As String
) As IRegionBehavior
	Get
```

### Parameters

key  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

### Property Value

Type: [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)  
The RegionBehavior that's registered with the key.

### Implements

[IRegionBehaviorCollection.Item[String]](/patterns-practices/reference/iregionbehaviorcollection-item-property-mspp-regions)

## See Also

[RegionBehaviorCollection Class](/patterns-practices/reference/regionbehaviorcollection-class-mspp-regions)<br/>
[RegionBehaviorCollection Members](/patterns-practices/reference/regionbehaviorcollection-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>