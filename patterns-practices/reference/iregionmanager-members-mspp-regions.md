---
TOCTitle: IRegionManager Members
Title: 'IRegionManager Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionManager'
ms:mtpsurl: 'iregionmanager-members-mspp-regions.md'
---


# IRegionManager Members

The [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) type exposes the following members.

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
<td><a href="/patterns-practices/reference/iregionmanager-createregionmanager-method-mspp-regions
">CreateRegionManager</a></td>
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
<td><a href="/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions
">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions">RegisterViewWithRegion(String, Func&lt;Object&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, String, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
">RequestNavigate(String, String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
">RegionManagerExtensions</a>.)</td>
</tr>
</tbody>
</table>

## Properties


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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="/patterns-practices/reference/iregionmanager-regions-property-mspp-regions
">Regions</a></td>
<td><div class="summary">
Gets a collection of <a href="/patterns-practices/reference/iregion-interface-mspp-regions
">IRegion</a> that identify each region by name. You can use this collection to add or remove regions to the current region manager.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionManager Interface](/patterns-practices/reference/iregionmanager-interface-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)