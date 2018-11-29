---
TOCTitle: IRegionNavigationJournal Members
Title: 'IRegionNavigationJournal Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal'
ms:mtpsurl: 'iregionnavigationjournal-members-mspp-regions.md'
---


# IRegionNavigationJournal Members

The [IRegionNavigationJournal](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal) type exposes the following members.

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
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.clear" data-raw-source="[Clear](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.clear)">Clear</a></td>
<td><div class="summary">
Clears the journal of current, back, and forward navigation histories.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goback" data-raw-source="[GoBack](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goback)">GoBack</a></td>
<td><div class="summary">
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goforward" data-raw-source="[GoForward](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goforward)">GoForward</a></td>
<td><div class="summary">
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.recordnavigation" data-raw-source="[RecordNavigation](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.recordnavigation)">RecordNavigation</a></td>
<td><div class="summary">
Records the navigation to the entry..
</div></td>
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
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoback" data-raw-source="[CanGoBack](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoback)">CanGoBack</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the back navigation history.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoforward" data-raw-source="[CanGoForward](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoforward)">CanGoForward</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the forward navigation history.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.currententry" data-raw-source="[CurrentEntry](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.currententry)">CurrentEntry</a></td>
<td><div class="summary">
Gets the current navigation entry of the content that is currently displayed.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.navigationtarget" data-raw-source="[NavigationTarget](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.navigationtarget)">NavigationTarget</a></td>
<td><div class="summary">
Gets or sets the target that implements INavigateAsync.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionNavigationJournal Interface](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)