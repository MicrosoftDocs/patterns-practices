---
TOCTitle: IRegionNavigationService Members
Title: 'IRegionNavigationService Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionNavigationService'
ms:mtpsurl: 'iregionnavigationservice-members-mspp-regions.md'
---


# IRegionNavigationService Members

The [IRegionNavigationService](/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions) type exposes the following members.

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
<td>[RequestNavigate(Uri, Action(NavigationResult))](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-mspp-regions)</td>
<td><div class="summary">
Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).
</div>
(Inherited from [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action(NavigationResult), NavigationParameters)](/patterns-practices/reference/mspp-regions-namespace.inavigateasync.requestnavigate)</td>
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
Initiates navigation to the target specified by the target.
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
<td>[RequestNavigate(String, Action(NavigationResult))](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(Uri, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-uri-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by [NavigationAsyncExtensions](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Action(NavigationResult), NavigationParameters)](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
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
<td>[Journal](/patterns-practices/reference/iregionnavigationservice-journal-property-mspp-regions)</td>
<td><div class="summary">
Gets the journal.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Region](/patterns-practices/reference/iregionnavigationservice-region-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the region owning this service.
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
<td>[Navigated](/patterns-practices/reference/iregionnavigationservice-navigated-event-mspp-regions)</td>
<td><div class="summary">
Raised when the region is navigated to content.
</div></td>
</tr>
<tr class="even">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[Navigating](/patterns-practices/reference/iregionnavigationservice-navigating-event-mspp-regions)</td>
<td><div class="summary">
Raised when the region is about to be navigated to content.
</div></td>
</tr>
<tr class="odd">
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[NavigationFailed](/patterns-practices/reference/iregionnavigationservice-navigationfailed-event-mspp-regions)</td>
<td><div class="summary">
Raised when a navigation request fails.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionNavigationService Interface](/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)