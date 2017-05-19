---
TOCTitle: ContainsRegionWithName Method
Title: 'IRegionCollection.ContainsRegionWithName Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionCollection.ContainsRegionWithName(System.String)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405964(v=PandP.50)'
---

# IRegionCollection.ContainsRegionWithName Method

Checks if the collection contains a [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) with the name received as parameter.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
bool ContainsRegionWithName(
	string regionName
)
```

```VB
'Declaration
Function ContainsRegionWithName ( 
	regionName As String
) As Boolean
```

#### Parameters

*regionName*

      Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
      The name of the region to look for.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)<br/>
**truetrue** (**True** in Visual Basic) if the region is contained in the collection, otherwise **falsefalse** (**False** in Visual Basic).

## See Also

[IRegionCollection Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregioncollection(v=pandp.50))

[IRegionCollection Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregioncollection_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))