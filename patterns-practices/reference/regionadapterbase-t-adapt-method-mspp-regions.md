---
TOCTitle: Adapt Method
Title: 'RegionAdapterBase(T).Adapt Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.Adapt(Microsoft.Practices.Prism.Regions.IRegion,\`0)'
ms:mtpsurl: 'regionadapterbase-t-adapt-method-mspp-regions.md'
---

# RegionAdapterBase&lt;T&gt;.Adapt Method

Template method to adapt the object to an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected abstract void Adapt(
	IRegion region,
	T regionTarget
)
```

### Parameters

*region*

Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

The new region being used.

*regionTarget*

Type: [T](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)

The object to adapt.

## See Also

[RegionAdapterBase&lt;T&gt; Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)

[RegionAdapterBase&lt;T&gt; Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)


# RegionAdapterBase(Of T).Adapt Method

Template method to adapt the object to an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Protected MustOverride Sub Adapt ( 
	region As IRegion,
	regionTarget As T
)
```

### Parameters

*region*

Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

The new region being used.

*regionTarget*

Type: [T](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)

The object to adapt.

## See Also

[RegionAdapterBase(Of T) Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)

[RegionAdapterBase(Of T) Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
