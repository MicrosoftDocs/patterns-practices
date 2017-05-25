---
TOCTitle: RegionManagerExtensions Members
Title: 'RegionManagerExtensions Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionManagerExtensions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405508(v=PandP.50)'
---


# RegionManagerExtensions Members

The [RegionManagerExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions) type exposes the following members.

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
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.add(microsoft.practices.prism.regions.iregioncollection%2csystem.string%2cmicrosoft.practices.prism.regions.iregion)">Add</a></td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.addtoregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.object)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(IRegionManager, String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string)">RequestNavigate(IRegionManager, String, String)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri)">RequestNavigate(IRegionManager, String, Uri)</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(IRegionManager, String, String, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(IRegionManager, String, Uri, NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(IRegionManager, String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td><div class="summary">
Navigates the specified region manager.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(IRegionManager, String, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405508.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.requestnavigate(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(IRegionManager, String, Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td><div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
