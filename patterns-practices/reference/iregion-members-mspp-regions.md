---
TOCTitle: IRegion Members
Title: 'IRegion Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'iregion-members-mspp-regions.md'
---

# IRegion Members

The [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) type exposes the following members.

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
<td>[Activate](/patterns-practices/reference/iregion-activate-method-mspp-regions)</td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object)](/patterns-practices/reference/iregion-add-method-object-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String)](/patterns-practices/reference/iregion-add-method-object-string-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String, Boolean)](/patterns-practices/reference/iregion-add-method-object-string-boolean-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Deactivate](/patterns-practices/reference/iregion-deactivate-method-mspp-regions)</td>
<td><div class="summary">
Marks the specified view as inactive.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetView](/patterns-practices/reference/iregion-getview-method-mspp-regions)</td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Remove](/patterns-practices/reference/iregion-remove-method-mspp-regions)</td>
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
(Inherited from [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions
)</td>
<td><div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Inherited from [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions).)</td>
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
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-navigationparameters-mspp-regions
)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
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
<td>[ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](/patterns-practices/reference/iregion-behaviors-property-mspp-regions)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](/patterns-practices/reference/iregion-context-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](/patterns-practices/reference/iregion-name-property-mspp-regions)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](/patterns-practices/reference/iregion-navigationservice-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the navigation service.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](/patterns-practices/reference/iregion-regionmanager-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as **Truetrue** (**True** in Visual Basic).
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](/patterns-practices/reference/iregion-sortcomparison-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](/patterns-practices/reference/iregion-views-property-mspp-regions)</td>
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

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  