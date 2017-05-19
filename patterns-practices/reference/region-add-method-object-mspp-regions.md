---
TOCTitle: 'Add Method (Object)'
Title: 'Region.Add Method (Object) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.Add(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418984(v=PandP.50)'
---

Prism Class Library

Region.Add Method (Object)
==============================

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public IRegionManager Add( Object view )Public Function Add ( view As Object ) As IRegionManager
#### Parameters

view  
Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The view to add.

#### Return Value

Type: [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that is set on the view if it is a [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309). It will be the current region manager when using this overload.
#### Implements

[IRegion.Add(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object))

See Also
--------


[Region Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region)

[Region Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.region)

[Add Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.region.add)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
