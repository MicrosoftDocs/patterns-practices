---
TOCTitle: IRegionManager Members
Title: 'IRegionManager Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405477(v=PandP.50)'
---

Prism Class Library

IRegionManager Members
======================

Include Protected Members
Include Inherited Members

The [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405477.pubmethod(en-us,PandP.50).gif "Public method")
[CreateRegionManager](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionmanager.createregionmanager)
Creates a new region manager.

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[AddToRegion](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object))
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RegisterViewWithRegion(String, Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type))
Overloaded.
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d))
Overloaded.
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg405477.pubproperty(en-us,PandP.50).gif "Public property")
[Regions](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregionmanager.regions)
Gets a collection of [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) that identify each region by name. You can use this collection to add or remove regions to the current region manager.

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegionManager Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
