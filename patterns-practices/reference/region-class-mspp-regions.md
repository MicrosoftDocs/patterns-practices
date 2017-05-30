---
TOCTitle: Region Class
Title: 'Region Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Region'
ms:mtpsurl: 'region-class-mspp-regions.md'
---

# Region Class

Implementation of [IRegion](iregion-interface-mspp-regions) that allows multiple active views.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace)

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

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
  Microsoft.Practices.Prism.Regions.Region<br/>
    [Microsoft.Practices.Prism.Regions.AllActiveRegion](allactiveregion-class-mspp-regions)<br/>
    [Microsoft.Practices.Prism.Regions.SingleActiveRegion](singleactiveregion-class-mspp-regions)

## See Also

[Region Members](region-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace)