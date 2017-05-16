---
TOCTitle: RegisterViewWithRegion Method
Title: 'RegionManagerExtensions.RegisterViewWithRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RegisterViewWithRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419137(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions..::.RegisterViewWithRegion Method
=========================================================

Include Protected Members
Include Inherited Members

Overload List
-------------

<span id="overloadMembersTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg419137.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg419137.static(en-us,PandP.50).gif "Static member")
[RegisterViewWithRegion(IRegionManager, String, Func&lt;(Of &lt;(Object&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d))
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.

![](https://msdn.microsoft.com/en-us/Gg419137.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg419137.static(en-us,PandP.50).gif "Static member")
[RegisterViewWithRegion(IRegionManager, String, Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type))
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
