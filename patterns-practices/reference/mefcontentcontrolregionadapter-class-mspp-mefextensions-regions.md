---
TOCTitle: MefContentControlRegionAdapter Class
Title: 'MefContentControlRegionAdapter Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter'
ms:mtpsurl: 'mefcontentcontrolregionadapter-class-mspp-mefextensions-regions.md'
---

# MefContentControlRegionAdapter Class

Exports the ContentControlRegionAdapter using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefContentControlRegionAdapter : ContentControlRegionAdapter
```

## Remarks

This allows the [ConfigureContainer()](/patterns-practices/reference/mefbootstrapper-configurecontainer-method-mspp-mefextensions) to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)&lt;[ContentControl](http://msdn.microsoft.com/en-us/library/ms609797)&gt;  
[Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter

```VB
'Declaration
Public Class MefContentControlRegionAdapter
	Inherits ContentControlRegionAdapter
```

## Remarks

This allows the [ConfigureContainer](/patterns-practices/reference/mefbootstrapper-configurecontainer-method-mspp-mefextensions) to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)(Of [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797))  
[Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter

## See Also

[MefContentControlRegionAdapter Members](/patterns-practices/reference/mefcontentcontrolregionadapter-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)