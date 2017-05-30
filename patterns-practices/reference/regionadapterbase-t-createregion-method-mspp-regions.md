---
TOCTitle: CreateRegion Method
Title: 'RegionAdapterBase(T).CreateRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.CreateRegion'
ms:mtpsurl: 'regionadapterbase-t-createregion-method-mspp-regions.md'
---

# RegionAdapterBase(Of T).CreateRegion Method

Template method to create a new instance of [IRegion](iregion-interface-mspp-regions) that will be used to adapt the object.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
    protected abstract IRegion CreateRegion()
```
```VB
    'Declaration
    Protected MustOverride Function CreateRegion As IRegion
```

### Return Value

Type: [IRegion](iregion-interface-mspp-regions)

A new instance of [IRegion](iregion-interface-mspp-regions).

## See Also
[RegionAdapterBase(Of T) Class](regionadapterbase-t-class-mspp-regions)

[RegionAdapterBase(Of T) Members](regionadapterbase-t-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace)
