---
TOCTitle: Remove Method
Title: 'IRegionCollection.Remove Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionCollection.Remove(System.String)'
ms:mtpsurl: 'iregioncollection-remove-method-mspp-regions.md'
---

# IRegionCollection.Remove Method

Removes a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) from the collection.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool Remove(
	string regionName
)
```

```VB
'Declaration
Function Remove ( 
	regionName As String
) As Boolean
```

### Parameters

*regionName*

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Name of the region to be removed.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**Truetrue** (**True** in Visual Basic) if the region was removed from the collection, otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[IRegionCollection Interface](/patterns-practices/reference/iregioncollection-interface-mspp-regions)<br/>
[IRegionCollection Members](/patterns-practices/reference/iregioncollection-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>