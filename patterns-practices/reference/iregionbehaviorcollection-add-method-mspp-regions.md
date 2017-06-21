---
TOCTitle: Add Method
Title: 'IRegionBehaviorCollection.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionBehaviorCollection.Add(System.String,Microsoft.Practices.Prism.Regions.IRegionBehavior)'
ms:mtpsurl: 'iregionbehaviorcollection-add-method-mspp-regions.md'
---

# IRegionBehaviorCollection.Add Method

Adds a [IRegionBehavior](/patterns-practices/reference/mspp-regions-namespace) to the collection, using the specified key as an indexer.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
void Add(
	string key,
	IRegionBehavior regionBehavior
)
```

```VB
'Declaration
Sub Add ( 
	key As String,
	regionBehavior As IRegionBehavior
)
```

### Parameters

*key*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The key that specifies the type of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) that's added.

*regionBehavior*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) to add.

## See Also

[IRegionBehaviorCollection Interface](/patterns-practices/reference/iregionbehaviorcollection-interface-mspp-regions)  
[IRegionBehaviorCollection Members](/patterns-practices/reference/iregionbehaviorcollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  