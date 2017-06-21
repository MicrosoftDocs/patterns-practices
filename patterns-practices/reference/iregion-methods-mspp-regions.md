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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Activate](/patterns-practices/reference/iregion-activate-method-mspp-regions)</td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object)](/patterns-practices/reference/iregion-add-method-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String)](/patterns-practices/reference/iregion-add-method-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String, Boolean)](/patterns-practices/reference/iregion-add-method-mspp-regions)</td>
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
<td>[RequestNavigate(Uri, Action(Of NavigationResult))](/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions)</td>
<td><div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Inherited from [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/inavigateasync-requestnavigate-method-mspp-regions)</td>
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
<td>[RequestNavigate(String)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action(Of NavigationResult))](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the *target*.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions.)</td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  