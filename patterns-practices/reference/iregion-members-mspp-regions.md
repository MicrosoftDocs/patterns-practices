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
<td>[Activate](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activate(system.object))</td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object))</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string))</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String, Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean))</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Deactivate](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.deactivate(system.object))</td>
<td><div class="summary">
Marks the specified view as inactive.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetView](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.getview(system.string))</td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Remove](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.remove(system.object))</td>
<td><div class="summary">
Removes the specified view from the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions)</td>
<td><div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Inherited from [INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions
)</td>
<td><div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Inherited from [INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync).)</td>
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
<td>[RequestNavigate(String)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <i>target.</i>
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri))</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <i>target.</i>
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri, NavigationParameters)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <i>target.</i>
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-navigationparameters-mspp-regions
)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <i>target.</i>
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <i>target.</i>
</div>
(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions).)</td>
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
<td>[ActiveViews](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activeviews)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.behaviors)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.context)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.name)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.navigationservice)</td>
<td><div class="summary">
Gets or sets the navigation service.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.regionmanager)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <b>truetrue</b> (<b>True</b> in Visual Basic).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.sortcomparison)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.views)</td>
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
<td>[PropertyChanged](http://msdn.microsoft.com/en-us/library/ms133023)</td>
<td><div class="summary">
Occurs when a property value changes.
</div>
(Inherited from [INotifyPropertyChanged](http://msdn.microsoft.com/en-us/library/ms133020).)</td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)<br/>
[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)<br/>