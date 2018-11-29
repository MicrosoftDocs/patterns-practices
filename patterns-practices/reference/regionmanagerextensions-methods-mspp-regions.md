---
TOCTitle: RegionManagerExtensions Methods
Title: 'RegionManagerExtensions Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.RegionManagerExtensions'
ms:mtpsurl: 'regionmanagerextensions-methods-mspp-regions.md'
---

# RegionManagerExtensions Methods

The [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions) type exposes the following members.

## Methods

<table>
<colgroup>
<col width="150">
<col>
<col>
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions" data-raw-source="[Add](/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions)">Add</a></td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions" data-raw-source="[AddToRegion](/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions" data-raw-source="[RegisterViewWithRegion(IRegionManager, String, Func&amp;lt;Object&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions)">RegisterViewWithRegion(IRegionManager, String, Func&lt;Object&gt;)</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get&#39;s displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions" data-raw-source="[RegisterViewWithRegion(IRegionManager, String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions)">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get&#39;s displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)">RequestNavigate(IRegionManager, String, String)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions)">RequestNavigate(IRegionManager, String, Uri)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions)">RequestNavigate(IRegionManager, String, String, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, String, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)">RequestNavigate(IRegionManager, String, String, Action&lt;NavigationResult&gt;)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions)">RequestNavigate(IRegionManager, String, Uri, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, Uri, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-mspp-regions)">RequestNavigate(IRegionManager, String, Uri, Action&lt;NavigationResult&gt;)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, String, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(IRegionManager, String, String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(IRegionManager, String, Uri, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(IRegionManager, String, Uri, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)