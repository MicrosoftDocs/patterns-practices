---
TOCTitle: MefRegionViewRegistry Class
Title: 'MefRegionViewRegistry Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionViewRegistry'
ms:mtpsurl: 'mefregionviewregistry-class-mspp-mefextensions-regions.md'
---

# MefRegionViewRegistry Class

Exports the RegionViewRegistry using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionViewRegistry : RegionViewRegistry
```

```VB
'Declaration
Public Class MefRegionViewRegistry
	Inherits RegionViewRegistry
```

## Remarks

&nbsp;&nbsp;This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

&nbsp;&nbsp;[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Regions.RegionViewRegistry](/patterns-practices/reference/regionviewregistry-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionViewRegistry

## See Also

[MefRegionViewRegistry Members](/patterns-practices/reference/mefregionviewregistry-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)