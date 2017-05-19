---
TOCTitle: RegionManager Methods
Title: 'RegionManager Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.RegionManager'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431109(v=PandP.50)'
---

Prism Class Library

RegionManager Methods
=====================

The [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.createregionmanager">CreateRegionManager</a></td>
<td><div class="summary">
Creates a new region manager.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getobservableregion(system.windows.dependencyobject)">GetObservableRegion</a></td>
<td><div class="summary">
Returns an <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601">ObservableObject&lt;(Of &lt;(T&gt;)&gt;)</a> wrapper that can hold an <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a>. Using this wrapper you can detect when an <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> has been created by the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadapterbase%601">RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;)</a>. If the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.observableobject%601">ObservableObject&lt;(Of &lt;(T&gt;)&gt;)</a> wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the <a href="https://msdn.microsoft.com/e:microsoft.practices.prism.observableobject%601.propertychanged">PropertyChanged</a> event to get notified of that change.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregioncontext(system.windows.dependencyobject)">GetRegionContext</a></td>
<td><div class="summary">
Gets the value of the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty">RegionContextProperty</a> attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregionmanager(system.windows.dependencyobject)">GetRegionManager</a></td>
<td><div class="summary">
Gets the value of the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty">RegionNameProperty</a> attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.getregionname(system.windows.dependencyobject)">GetRegionName</a></td>
<td><div class="summary">
Gets the value for the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty">RegionNameProperty</a> attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregioncontext(system.windows.dependencyobject%2csystem.object)">SetRegionContext</a></td>
<td><div class="summary">
Sets the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty">RegionContextProperty</a> attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregionmanager(system.windows.dependencyobject%2cmicrosoft.practices.prism.regions.iregionmanager)">SetRegionManager</a></td>
<td><div class="summary">
Sets the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty">RegionManagerProperty</a> attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.setregionname(system.windows.dependencyobject%2csystem.string)">SetRegionName</a></td>
<td><div class="summary">
Sets the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionnameproperty">RegionNameProperty</a> attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg431109.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanager.updateregions">UpdateRegions</a></td>
<td><div class="summary">
Notifies attached behaviors to update the region managers appropriatelly if needed to.
</div></td>
</tr>
</tbody>
</table>

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri)">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string)">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431109.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManager Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
