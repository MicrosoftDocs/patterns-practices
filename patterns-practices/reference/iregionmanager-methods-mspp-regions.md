---
TOCTitle: IRegionManager Methods
Title: 'IRegionManager Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegionManager'
ms:mtpsurl: 'iregionmanager-methods-mspp-regions.md'
---

# IRegionManager Methods

The [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) type exposes the following members.

## Methods


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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager.createregionmanager">CreateRegionManager</a></td>
<td><div class="summary">
Creates a new region manager.
</div></td>
</tr>
</tbody>
</table>

## Extension Methods


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
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri)">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string)">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions">RegionManagerExtensions</a>.)</td>
</tr>
</tbody>
</table>

## See Also
[IRegionManager Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
