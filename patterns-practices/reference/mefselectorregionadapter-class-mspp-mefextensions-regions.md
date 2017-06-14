---
TOCTitle: MefSelectorRegionAdapter Class
Title: 'MefSelectorRegionAdapter Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefSelectorRegionAdapter'
ms:mtpsurl: 'mefselectorregionadapter-class-mspp-mefextensions-regions.md'
---

# MefSelectorRegionAdapter Class

Exports the SelectorRegionAdapter using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefSelectorRegionAdapter : SelectorRegionAdapter
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)&lt;[Selector](http://msdn2.microsoft.com/en-us/library/ms595227)&gt;  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefSelectorRegionAdapter

```VB
'Declaration
Public Class MefSelectorRegionAdapter
	Inherits SelectorRegionAdapter
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)(Of [Selector](http://msdn.microsoft.com/en-us/library/ms595227))  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.SelectorRegionAdapter](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefSelectorRegionAdapter

## See Also

[MefSelectorRegionAdapter Members](/patterns-practices/reference/mefselectorregionadapter-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)