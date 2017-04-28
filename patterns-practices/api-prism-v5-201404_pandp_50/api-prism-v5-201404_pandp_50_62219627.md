---
TOCTitle: RegionManagerExtensions Members
Title: 'RegionManagerExtensions Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionManagerExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405508(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions Members
===============================

Include Protected Members
Include Inherited Members

The [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[Add](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.add(microsoft.practices.prism.regions.iregioncollection%2csystem.string%2cmicrosoft.practices.prism.regions.iregion))
Adds a region to the regionmanager with the name received as argument.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[AddToRegion](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object))
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RegisterViewWithRegion(IRegionManager, String, Func&lt;(Of &lt;(Object&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d))
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RegisterViewWithRegion(IRegionManager, String, Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type))
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string))
Navigates the specified region manager.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, Uri)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri))
Navigates the specified region manager.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, String, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters))
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Navigates the specified region manager.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, Uri, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Navigates the specified region manager.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

![](https://msdn.microsoft.com/en-us/Gg405508.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif "Static member")
[RequestNavigate(IRegionManager, String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
