---
TOCTitle: Item Property
Title: 'IRegionBehaviorCollection.Item Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.IRegionBehaviorCollection.Item(System.String)'
ms:mtpsurl: 'iregionbehaviorcollection-item-property-mspp-regions.md'
---

# IRegionBehaviorCollection.Item Property

Gets the [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) with the specified key.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegionBehavior this[
	string key
] { get; }
```

```VB
'Declaration
ReadOnly Default Property Item ( 
	key As String
) As IRegionBehavior
	Get
```

### Parameters

*key*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

### Property Value

Type: [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)  
The registered [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)

## See Also

[IRegionBehaviorCollection Interface](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)  
[IRegionBehaviorCollection Members](/patterns-practices/reference/iregionbehaviorcollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>