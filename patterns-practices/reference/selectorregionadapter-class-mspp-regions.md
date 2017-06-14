---
TOCTitle: SelectorRegionAdapter Class
Title: 'SelectorRegionAdapter Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.SelectorRegionAdapter'
ms:mtpsurl: 'selectorregionadapter-class-mspp-regions.md'
---


# SelectorRegionAdapter Class

Adapter that creates a new [Region](/patterns-practices/reference/region-class-mspp-regions) and binds all the views to the adapted [Selector](http://msdn.microsoft.com/en-us/library/ms595227). It also keeps the [ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions) and the selected items of the [Selector](http://msdn-microsoft-com/en-us/library/ms595227) in sync-

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public class SelectorRegionAdapter : RegionAdapterBase<Selector>
```
## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionAdapterBase](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadapterbase%601)&lt;[Selector](http://msdn.microsoft.com/en-us/library/ms595227)&gt;  
    Microsoft.Practices.Prism.Regions.SelectorRegionAdapter  
      [Microsoft-Practices-Prism-MefExtensions-Regions-MefSelectorRegionAdapter](/patterns-practices/reference/mefselectorregionadapter-class-mspp-mefextensions-regions)

```VB
'Declaration
Public Class SelectorRegionAdapter
	Inherits RegionAdapterBase(Of Selector)
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  [Microsoft.Practices.Prism.Regions.RegionAdapterBase](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionadapterbase%601)(Of [Selector](http://msdn.microsoft.com/en-us/library/ms595227))  
    Microsoft.Practices.Prism.Regions.SelectorRegionAdapter  
      [Microsoft-Practices-Prism-MefExtensions-Regions-MefSelectorRegionAdapter](/patterns-practices/reference/mefselectorregionadapter-class-mspp-mefextensions-regions)

## See Also

[SelectorRegionAdapter Members](/patterns-practices/reference/selectorregionadapter-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  