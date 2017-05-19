---
TOCTitle: AddToRegion Method
Title: 'RegionManagerExtensions.AddToRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.AddToRegion(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418952(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions.AddToRegion Method
==============================================

Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public static IRegionManager AddToRegion( this IRegionManager regionManager, string regionName, Object view )&lt;ExtensionAttribute&gt; Public Shared Function AddToRegion ( regionManager As IRegionManager, regionName As String, view As Object ) As IRegionManager
#### Parameters

regionManager  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The regionmanager that this extension method effects.

regionName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name of the region to add a view to

view  
Type: [System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
The view to add to the views collection

#### Return Value

Type: [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)
The RegionManager, to easily add several views.
#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

See Also
--------


[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
