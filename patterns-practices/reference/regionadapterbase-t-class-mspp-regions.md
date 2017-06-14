---
TOCTitle: 'RegionAdapterBase(T) Class'
Title: 'RegionAdapterBase(T) Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1'
ms:mtpsurl: 'regionadapterbase-t-class-mspp-regions.md'
---

# RegionAdapterBase&lt;T&gt; Class

Base class to facilitate the creation of [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) implementations.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public abstract class RegionAdapterBase<T> : IRegionAdapter
where T : class
```

###Type Parameters

*T*
  
Type of object to adapt.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  Microsoft.Practices.Prism.Regions.RegionAdapterBase&lt;T&gt;

    [Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)

    [Microsoft.Practices.Prism.Regions.ItemsControlRegionAdapter](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)

    [Microsoft.Practices.Prism.Regions.SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)

## See Also

[RegionAdapterBase&lt;T&gt; Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

# RegionAdapterBase(Of T) Class

Base class to facilitate the creation of [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions) implementations.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```VB
'Declaration
Public MustInherit Class RegionAdapterBase(Of T As Class)
	Implements IRegionAdapter
```

### Type Parameters

*T*
  
Type of object to adapt.

Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

  Microsoft.Practices.Prism.Regions.RegionAdapterBase(Of T)

    [Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)

    [Microsoft.Practices.Prism.Regions.ItemsControlRegionAdapter](
itemscontrolregionadapter-class-mspp-regions)

    [Microsoft.Practices.Prism.Regions.SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)

## See Also
[RegionAdapterBase(Of T) Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  
