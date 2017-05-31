---
TOCTitle: RegionManagerExtensions Members
Title: 'RegionManagerExtensions Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionManagerExtensions'
ms:mtpsurl: 'regionmanagerextensions-members-mspp-regions.md'
---

# RegionManagerExtensions Members

The [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions) type exposes the following members.

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
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions">Add</a></td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions">RegisterViewWithRegion(IRegionManager, String, Func(Of Object))</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions">RequestNavigate(IRegionManager, String, String)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions">RequestNavigate(IRegionManager, String, Uri)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions">RequestNavigate(IRegionManager, String, String, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions">RequestNavigate(IRegionManager, String, String, Action(Of NavigationResult))</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions">RequestNavigate(IRegionManager, String, Uri, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-mspp-regions">RequestNavigate(IRegionManager, String, Uri, Action(Of NavigationResult))</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions">RequestNavigate(IRegionManager, String, String, Action(Of NavigationResult), NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions">RequestNavigate(IRegionManager, String, Uri, Action(Of NavigationResult), NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
