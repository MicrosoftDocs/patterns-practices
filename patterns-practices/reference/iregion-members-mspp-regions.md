---
TOCTitle: IRegion Members
Title: 'IRegion Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'iregion-members-mspp-regions.md'
---


# IRegion Members

The [IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion) type exposes the following members.

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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activate(system.object)">Activate</a></td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object)">Add(Object)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string)">Add(Object, String)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean)">Add(Object, String, Boolean)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.deactivate(system.object)">Deactivate</a></td>
<td><div class="summary">
Marks the specified view as inactive.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.getview(system.string)">GetView</a></td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.remove(system.object)">Remove</a></td>
<td><div class="summary">
Removes the specified view from the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(Uri, Action&lt;NavigationResult&gt;)</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a>.)</td>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string)">RequestNavigate(String)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri)">RequestNavigate(Uri)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736275(v=pandp.50)">RequestNavigate(String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activeviews">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.behaviors">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a>s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.context">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.name">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.navigationservice">NavigationService</a></td>
<td><div class="summary">
Gets or sets the navigation service.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.regionmanager">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <b>truetrue</b> (<b>True</b> in Visual Basic).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.sortcomparison">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.views">Views</a></td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div></td>
</tr>
</tbody>
</table>

## Events


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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms133023">PropertyChanged</a></td>
<td><div class="summary">
Occurs when a property value changes.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms133020">INotifyPropertyChanged</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
