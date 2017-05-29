---
TOCTitle: MefRegionNavigationContentLoader Class
Title: 'MefRegionNavigationContentLoader Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader'
ms:mtpsurl: 'mefregionnavigationcontentloader-class-mspp-mefextensions-regions.md'
---

# MefRegionNavigationContentLoader Class

Exports the LocatorNavigationTargetHandler using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](mspp-mefextensions-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionNavigationContentLoader : RegionNavigationContentLoader
```

```VB
'Declaration
Public Class MefRegionNavigationContentLoader
	Inherits RegionNavigationContentLoader
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)</br>
  [Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader](regionnavigationcontentloader-class-mspp-regions.md)<br/>
    Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader

## See Also

[MefRegionNavigationContentLoader Members](mefregionnavigationcontentloader-members-mspp-mefextensions-regions.md)

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](mspp-mefextensions-regions-namespace.md)