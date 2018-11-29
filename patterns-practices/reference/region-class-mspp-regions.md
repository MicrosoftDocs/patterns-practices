---
TOCTitle: Region Class
Title: 'Region Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Region'
ms:mtpsurl: 'region-class-mspp-regions.md'
---

# Region Class

Implementation of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that allows multiple active views.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class Region : IRegion, INavigateAsync, 
	INotifyPropertyChanged
```

```VB
'Declaration
Public Class Region
	Implements IRegion, INavigateAsync, INotifyPropertyChanged
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  Microsoft.Practices.Prism.Regions.Region  
    [Microsoft.Practices.Prism.Regions.AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions)  
    [Microsoft.Practices.Prism.Regions.SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions)

## See Also

[Region Members](/patterns-practices/reference/region-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)