---
TOCTitle: MefItemsControlRegionAdapter Class
Title: 'MefItemsControlRegionAdapter Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefItemsControlRegionAdapter'
ms:mtpsurl: 'mefitemscontrolregionadapter-class-mspp-mefextensions-regions.md'
---

# MefItemsControlRegionAdapter Class

Exports the ItemsControlRegionAdapter using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefItemsControlRegionAdapter : ItemsControlRegionAdapter
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)&lt;[ItemsControl]( http://msdn.microsoft.com/en-us/library/ms611045)&gt;  
[Microsoft.Practices.Prism.Regions.ItemsControlRegionAdapter](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefItemsControlRegionAdapter

```VB
'Declaration
Public Class MefItemsControlRegionAdapter
	Inherits ItemsControlRegionAdapter
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)(Of [ItemsControl](http://msdn2.microsoft.com/en-us/library/ms611045))  
[Microsoft.Practices.Prism.Regions.ItemsControlRegionAdapter](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefItemsControlRegionAdapter

## See Also

[MefItemsControlRegionAdapter Members](/patterns-practices/reference/mefitemscontrolregionadapter-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)