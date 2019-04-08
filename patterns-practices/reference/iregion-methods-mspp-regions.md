---
TOCTitle: IRegion Methods
Title: 'IRegion Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'iregion-methods-mspp-regions.md'
---

# IRegion Methods

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
<td><a href="/patterns-practices/reference/iregion-add-method-mspp-regions" data-raw-source="[Add(Object)](/patterns-practices/reference/iregion-add-method-mspp-regions)">Add(Object)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-add-method-mspp-regions" data-raw-source="[Add(Object, String)](/patterns-practices/reference/iregion-add-method-mspp-regions)">Add(Object, String)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregion-add-method-mspp-regions" data-raw-source="[Add(Object, String, Boolean)](/patterns-practices/reference/iregion-add-method-mspp-regions)">Add(Object, String, Boolean)</a></td>
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
<td><a href="/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(Uri, Action(Of NavigationResult))](/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions)">RequestNavigate(Uri, Action(Of NavigationResult))</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/inavigateasync-interface-mspp-regions" data-raw-source="[INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)">INavigateAsync</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(Uri, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions)">RequestNavigate(Uri, Action(Of NavigationResult), NavigationParameters)</a></td>
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
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)">RequestNavigate(String)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(Uri)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)">RequestNavigate(Uri)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn.microsoft.com/en-us/library/txt7706a" data-raw-source="[Uri](http://msdn.microsoft.com/en-us/library/txt7706a)">Uri</a>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, Action(Of NavigationResult))](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)">RequestNavigate(String, Action(Of NavigationResult))</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(Uri, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)">RequestNavigate(Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions" data-raw-source="[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)">RequestNavigate(String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(String, Action(Of NavigationResult), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <em>target</em>.
</div>
(Defined by <a href="/patterns-practices/reference/navigationasyncextensions-class-mspp-regions." data-raw-source="[NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)">NavigationAsyncExtensions</a></td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  