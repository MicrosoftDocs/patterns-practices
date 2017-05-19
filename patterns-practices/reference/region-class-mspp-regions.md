---
TOCTitle: Region Class
Title: 'Region Class (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.Regions.Region'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431545(v=PandP.50)'
---

# Region Class

Implementation of [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) that allows multiple active views.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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

[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)<br/>
  Microsoft.Practices.Prism.Regions.Region<br/>
    [Microsoft.Practices.Prism.Regions.AllActiveRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.allactiveregion(v=pandp.50))<br/>
    [Microsoft.Practices.Prism.Regions.SingleActiveRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.singleactiveregion(v=pandp.50))

## See Also

[Region Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))