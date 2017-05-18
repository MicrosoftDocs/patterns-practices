---
TOCTitle: RegionManager Methods
Title: 'RegionManager Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.RegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431109(v=PandP.50)'
---

Prism Class Library

RegionManager Methods
=====================

Include Protected Members
Include Inherited Members

The [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")
[CreateRegionManager](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.createregionmanager)
Creates a new region manager.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[GetObservableRegion](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getobservableregion(system.windows.dependencyobject))
Returns an [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper that can hold an [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion). Using this wrapper you can detect when an [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) has been created by the [RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadapterbase%601). If the [ObservableObject&lt;(Of &lt;(T&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601) wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the [PropertyChanged](https://msdn.microsoft.com/e:microsoft.practices.prism.observableobject%601.propertychanged) event to get notified of that change.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[GetRegionContext](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregioncontext(system.windows.dependencyobject))
Gets the value of the [RegionContextProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[GetRegionManager](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregionmanager(system.windows.dependencyobject))
Gets the value of the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[GetRegionName](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregionname(system.windows.dependencyobject))
Gets the value for the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[SetRegionContext](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregioncontext(system.windows.dependencyobject%2csystem.object))
Sets the [RegionContextProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[SetRegionManager](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregionmanager(system.windows.dependencyobject%2cmicrosoft.practices.prism.regions.iregionmanager))
Sets the [RegionManagerProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[SetRegionName](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregionname(system.windows.dependencyobject%2csystem.string))
Sets the [RegionNameProperty](https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty) attached property.

![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif "Public method")![](https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif "Static member")
[UpdateRegions](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.updateregions)
Notifies attached behaviors to update the region managers appropriatelly if needed to.

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[AddToRegion](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object))
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RegisterViewWithRegion(String, Type)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type))
Overloaded.
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d))
Overloaded.
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Navigates the specified region manager.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)
![](https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.

(Defined by [RegionManagerExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions).)

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
