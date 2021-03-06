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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregionmanager-createregionmanager-method-mspp-regions" data-raw-source="[CreateRegionManager](/patterns-practices/reference/iregionmanager-createregionmanager-method-mspp-regions
)">CreateRegionManager</a></td>
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
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions" data-raw-source="[AddToRegion](/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions
)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions" data-raw-source="[RegisterViewWithRegion(String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get&#39;s displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions" data-raw-source="[RegisterViewWithRegion(String, Func&amp;lt;Object&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-mspp-regions)">RegisterViewWithRegion(String, Func&lt;Object&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get&#39;s displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, String, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, String, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, String, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-mspp-regions
)">RequestNavigate(String, String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregionmanager-regions-property-mspp-regions" data-raw-source="[Regions](/patterns-practices/reference/iregionmanager-regions-property-mspp-regions
)">Regions</a></td>
<td><div class="summary">
Gets a collection of <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)">IRegion</a> that identify each region by name. You can use this collection to add or remove regions to the current region manager.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionManager Interface](/patterns-practices/reference/iregionmanager-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)