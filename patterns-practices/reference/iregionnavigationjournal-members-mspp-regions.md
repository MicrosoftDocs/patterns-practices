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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Clear](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.clear)</td>
<td><div class="summary">
Clears the journal of current, back, and forward navigation histories.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GoBack](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goback)</td>
<td><div class="summary">
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GoForward](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.goforward)</td>
<td><div class="summary">
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RecordNavigation](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.recordnavigation)</td>
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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CanGoBack](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoback)</td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the back navigation history.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CanGoForward](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.cangoforward)</td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the forward navigation history.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CurrentEntry](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.currententry)</td>
<td><div class="summary">
Gets the current navigation entry of the content that is currently displayed.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationTarget](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal.navigationtarget)</td>
<td><div class="summary">
Gets or sets the target that implements INavigateAsync.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionNavigationJournal Interface](/patterns-practices/reference/mspp-regions-namespace.iregionnavigationjournal)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)