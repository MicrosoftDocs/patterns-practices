---
TOCTitle: IRegionManager Members
Title: 'IRegionManager Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionManager'
ms:mtpsurl: 'iregionmanager-members-mspp-regions.md'
---

# IRegionManager Members

The [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) type exposes the following members.

## Methods

<span id="methodTableToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager.createregionmanager">CreateRegionManager</a></td>
<td><div class="summary">
Creates a new region manager.
</div></td>
</tr>
</tbody>
</table>

## Extension Methods

<span id="extensionMethodTableToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri)">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string)">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
</tbody>
</table>

## Properties

<span id="propertyTableToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405477.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager.regions">Regions</a></td>
<td><div class="summary">
Gets a collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> that identify each region by name. You can use this collection to add or remove regions to the current region manager.
</div></td>
</tr>
</tbody>
</table>

## See Also
[IRegionManager Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
