---
TOCTitle: RegionManagerExtensions Methods
Title: 'RegionManagerExtensions Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.RegionManagerExtensions'
ms:mtpsurl: 'regionmanagerextensions-methods-mspp-regions.md'
---

# RegionManagerExtensions Methods

The [RegionManagerExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions) type exposes the following members.

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[Add](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.add(microsoft.practices.prism.regions.iregioncollection%2csystem.string%2cmicrosoft.practices.prism.regions.iregion))</td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[AddToRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object))</td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RegisterViewWithRegion(IRegionManager, String, Func&lt;Object&gt;)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions)</td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RegisterViewWithRegion(IRegionManager, String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions)</td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)</td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions)</td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions)</td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, String, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)</td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions)</td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-mspp-regions)</td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, String, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RequestNavigate(IRegionManager, String, Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions)</td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions)  
[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)