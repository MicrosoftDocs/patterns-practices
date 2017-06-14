---
TOCTitle: MefContentControlRegionAdapter Class
Title: 'MefContentControlRegionAdapter Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter'
ms:mtpsurl: 'mefcontentcontrolregionadapter-class-mspp-mefextensions-regions.md'
---

# MefContentControlRegionAdapter Class

Exports the ContentControlRegionAdapter using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefContentControlRegionAdapter : ContentControlRegionAdapter
```

```VB
'Declaration
Public Class MefContentControlRegionAdapter
	Inherits ContentControlRegionAdapter
```

## Remarks

&nbsp;&nbsp;This allows the [ConfigureContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer) to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)&lt;[ContentControl](http://msdn.microsoft.com/en-us/library/ms609797)&gt;<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter

```VB
'Declaration
Public Class MefContentControlRegionAdapter
	Inherits ContentControlRegionAdapter
```

## Remarks

&nbsp;&nbsp;This allows the [ConfigureContainer](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer) to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionAdapterBase](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)(Of [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797))<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter

## See Also

[MefContentControlRegionAdapter Members](/patterns-practices/reference/mefcontentcontrolregionadapter-members-mspp-mefextensions-regions)<br/>
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)