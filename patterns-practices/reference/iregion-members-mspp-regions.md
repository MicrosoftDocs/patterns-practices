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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-activate-method-mspp-regions" data-raw-source="[Activate](/patterns-practices/reference/iregion-activate-method-mspp-regions)">Activate</a></td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-add-method-object-mspp-regions" data-raw-source="[Add(Object)](/patterns-practices/reference/iregion-add-method-object-mspp-regions)">Add(Object)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-add-method-object-string-mspp-regions" data-raw-source="[Add(Object, String)](/patterns-practices/reference/iregion-add-method-object-string-mspp-regions)">Add(Object, String)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-add-method-object-string-boolean-mspp-regions" data-raw-source="[Add(Object, String, Boolean)](/patterns-practices/reference/iregion-add-method-object-string-boolean-mspp-regions)">Add(Object, String, Boolean)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-deactivate-method-mspp-regions" data-raw-source="[Deactivate](/patterns-practices/reference/iregion-deactivate-method-mspp-regions)">Deactivate</a></td>
<td><div class="summary">
Marks the specified view as inactive.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-getview-method-mspp-regions" data-raw-source="[GetView](/patterns-practices/reference/iregion-getview-method-mspp-regions)">GetView</a></td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-remove-method-mspp-regions" data-raw-source="[Remove](/patterns-practices/reference/iregion-remove-method-mspp-regions)">Remove</a></td>
<td><div class="summary">
Removes the specified view from the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(Uri, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(Uri, Action&lt;NavigationResult&gt;)</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/inavigateasync-interface-mspp-regions" data-raw-source="[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)">INavigateAsync</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(Uri, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions
)">RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/inavigateasync-interface-mspp-regions" data-raw-source="[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)">INavigateAsync</a>.)</td>
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
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-mspp-regions" data-raw-source="[RequestNavigate(String)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-mspp-regions)">RequestNavigate(String)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-mspp-regions" data-raw-source="[RequestNavigate(Uri)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-mspp-regions)">RequestNavigate(Uri)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions" data-raw-source="[RequestNavigate(String, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions)">RequestNavigate(String, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(Uri, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-navigationparameters-mspp-regions)">RequestNavigate(Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-navigationparameters-mspp-regions
)">RequestNavigate(String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions" data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)">NavigationAsyncExtensions</a>.)</td>
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
<td><a href="/patterns-practices/reference/iregion-activeviews-property-mspp-regions" data-raw-source="[ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions)">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-behaviors-property-mspp-regions" data-raw-source="[Behaviors](/patterns-practices/reference/iregion-behaviors-property-mspp-regions)">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a>s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-context-property-mspp-regions" data-raw-source="[Context](/patterns-practices/reference/iregion-context-property-mspp-regions)">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-name-property-mspp-regions" data-raw-source="[Name](/patterns-practices/reference/iregion-name-property-mspp-regions)">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-navigationservice-property-mspp-regions" data-raw-source="[NavigationService](/patterns-practices/reference/iregion-navigationservice-property-mspp-regions)">NavigationService</a></td>
<td><div class="summary">
Gets or sets the navigation service.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-regionmanager-property-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/iregion-regionmanager-property-mspp-regions)">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <strong>Truetrue</strong> (<strong>True</strong> in Visual Basic).
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-sortcomparison-property-mspp-regions" data-raw-source="[SortComparison](/patterns-practices/reference/iregion-sortcomparison-property-mspp-regions)">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-views-property-mspp-regions" data-raw-source="[Views](/patterns-practices/reference/iregion-views-property-mspp-regions)">Views</a></td>
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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms133023" data-raw-source="[PropertyChanged](http://msdn.microsoft.com/en-us/library/ms133023)">PropertyChanged</a></td>
<td><div class="summary">
Occurs when a property value changes.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms133020" data-raw-source="[INotifyPropertyChanged](http://msdn.microsoft.com/en-us/library/ms133020)">INotifyPropertyChanged</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  