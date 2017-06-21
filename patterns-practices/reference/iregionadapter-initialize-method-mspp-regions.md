---
TOCTitle: Initialize Method
Title: 'IRegionAdapter.Initialize Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionAdapter.Initialize(System.Object,System.String)'
ms:mtpsurl: 'iregionadapter-initialize-method-mspp-regions.md'
---

# IRegionAdapter.Initialize Method

Adapts an object and binds it to a new [IRegion](/patterns-practices/reference/mspp-regions-namespace).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
IRegion Initialize(
	Object regionTarget,
	string regionName
)
```

```VB
'Declaration
Function Initialize ( 
	regionTarget As Object,
	regionName As String
) As IRegion
```

### Parameters

*regionTarget*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
The object to adapt.

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
The name of the region to be created.

### Return Value  
Type: [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The new instance of [IRegion](/patterns-practices/reference/mspp-regions-namespace) that the regionTarget is bound to.

## See Also

[IRegionAdapter Interface](/patterns-practices/reference/iregionadapter-interface-mspp-regions)  
[IRegionAdapter Members](/patterns-practices/reference/iregionadapter-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  