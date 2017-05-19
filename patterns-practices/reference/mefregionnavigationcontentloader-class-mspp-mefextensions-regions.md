---
TOCTitle: MefRegionNavigationContentLoader Class
Title: 'MefRegionNavigationContentLoader Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431465(v=PandP.50)'
---

# MefRegionNavigationContentLoader Class

Exports the LocatorNavigationTargetHandler using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions(v=pandp.50))

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

Inheritance Hierarchy
---------------------

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)</br>
  [Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationcontentloader(v=pandp.50))<br/>
    Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionNavigationContentLoader

## See Also

[MefRegionNavigationContentLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.mefregionnavigationcontentloader_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions(v=pandp.50))