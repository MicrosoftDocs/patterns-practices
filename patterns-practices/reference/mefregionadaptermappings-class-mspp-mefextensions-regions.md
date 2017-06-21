---
TOCTitle: MefRegionAdapterMappings Class
Title: 'MefRegionAdapterMappings Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionAdapterMappings'
ms:mtpsurl: 'mefregionadaptermappings-class-mspp-mefextensions-regions.md'
---

# MefRegionAdapterMappings Class

Exports the RegionAdapterMappings using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](/patterns-practices/reference/mspp-mefextensions-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefRegionAdapterMappings : RegionAdapterMappings
```

```VB
'Declaration
Public Class MefRegionAdapterMappings
	Inherits RegionAdapterMappings
```

## Remarks

This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Regions.RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)  
Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionAdapterMappings  

## See Also

[MefRegionAdapterMappings Members](/patterns-practices/reference/mefregionadaptermappings-members-mspp-mefextensions-regions)  
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)