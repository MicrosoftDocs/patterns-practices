---
TOCTitle: 'Add Method (Object, String, Boolean)'
Title: 'Region.Add Method (Object, String, Boolean) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.Add(System.Object,System.String,System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418986(v=PandP.50)'
---

Prism Class Library

Region.Add Method (Object, String, Boolean)
===============================================

Adds a new view to the region.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public virtual IRegionManager Add( Object view, string viewName, bool createRegionManagerScope )Public Overridable Function Add ( view As Object, viewName As String, createRegionManagerScope As Boolean ) As IRegionManager
#### Parameters

view  
Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The view to add.

viewName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name of the view. This can be used to retrieve it later by calling [GetView(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.getview(system.string)).

createRegionManagerScope  
Type: [System.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
When trueTruetruetrue (True in Visual Basic), the added view will receive a new instance of [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager), otherwise it will use the current region manager for this region.

#### Return Value

Type: [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that is set on the view if it is a [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309).
#### Implements

[IRegion.Add(Object, String, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean))

See Also
--------


[Region Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region)

[Region Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.region)

[Add Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.region.add)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
