---
TOCTitle: Item Property
Title: 'IRegionCollection.Item Property (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'P:Microsoft.Practices.Prism.Regions.IRegionCollection.Item(System.String)'
ms:mtpsurl: 'iregioncollection-item-property-mspp-regions.md'
---


# IRegionCollection.Item Property

Gets the IRegion with the name received as index.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
IRegion this[
	string regionName
] { get; }
```

```VB
'Declaration
ReadOnly Default Property Item ( 
	regionName As String
) As IRegion
	Get
```

### Parameters

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
Name of the region to be retrieved.

### Return Value

Type: [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) identified with the requested name.

## See Also

[IRegionCollection Interface](/patterns-practices/reference/iregioncollection-interface-mspp-regions)  
[IRegionCollection Members](/patterns-practices/reference/iregioncollection-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
