---
TOCTitle: Add Method
Title: 'RegionManagerExtensions.Add Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.Add(Microsoft.Practices.Prism.Regions.IRegionCollection,System.String,Microsoft.Practices.Prism.Regions.IRegion)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418953(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions.Add Method
======================================

Adds a region to the regionmanager with the name received as argument.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public static void Add( this IRegionCollection regionCollection, string regionName, IRegion region )&lt;ExtensionAttribute&gt; Public Shared Sub Add ( regionCollection As IRegionCollection, regionName As String, region As IRegion )
#### Parameters

regionCollection  
Type: [Microsoft.Practices.Prism.Regions.IRegionCollection](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregioncollection)
The regionmanager's collection of regions.

regionName  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)
The name to be given to the region.

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)
The region to be added to the regionmanager.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IRegionCollection](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregioncollection). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                                                                                  |
|---------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | Thrown if region or regionCollection is nullNothingnullptra null reference (Nothing in Visual Basic).                                                                                                                      |
| [System.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114)     | Thrown if regionName and region's name do not match and the region[Name](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.name) is not nullNothingnullptra null reference (Nothing in Visual Basic). |

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
