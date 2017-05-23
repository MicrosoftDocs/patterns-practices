---
TOCTitle: MefRegionManager Class
Title: 'MefRegionManager Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431464(v=PandP.50)'
---

# MefRegionManager Class

Exports the RegionManager using the Managed Extensibility Framework (MEF). 

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionManager : RegionManager
```

## Syntax

```VB
'Declaration
Public Class MefRegionManager
	Inherits RegionManager
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used. 

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionManager](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionmanager(v=pandp.50))
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionManage

## See Also

[MefRegionManager Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions.mefregionmanager_members(v=pandp.50))

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.mefextensions.regions(v=pandp.50))
