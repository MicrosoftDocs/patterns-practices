---
TOCTitle: MefRegionManager Class
Title: 'MefRegionManager Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionManager'
ms:mtpsurl: 'mefregionmanager-class-mspp-mefextensions-regions.md'
---

# MefRegionManager Class

Exports the RegionManager using the Managed Extensibility Framework (MEF). 

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionManager : RegionManager
```

```VB
'Declaration
Public Class MefRegionManager
	Inherits RegionManager
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used. 

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionManage

## See Also

[MefRegionManager Members](/patterns-practices/reference/mefregionmanager-members-mspp-mefextensions-regions)<br/>
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)