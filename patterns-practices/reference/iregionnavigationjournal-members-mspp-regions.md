---
TOCTitle: IRegionNavigationJournal Members
Title: 'IRegionNavigationJournal Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal'
ms:mtpsurl: 'iregionnavigationjournal-members-mspp-regions.md'
---


# IRegionNavigationJournal Members


The [IRegionNavigationJournal](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal(v=pandp.50)) type exposes the following members.

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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.clear(v=pandp.50)">Clear</a></td>
<td><div class="summary">
Clears the journal of current, back, and forward navigation histories.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.goback(v=pandp.50)">GoBack</a></td>
<td><div class="summary">
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.goforward(v=pandp.50)">GoForward</a></td>
<td><div class="summary">
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.recordnavigation(v=pandp.50)">RecordNavigation</a></td>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.cangoback(v=pandp.50)">CanGoBack</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the back navigation history.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.cangoforward(v=pandp.50)">CanGoForward</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the forward navigation history.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.currententry(v=pandp.50)">CurrentEntry</a></td>
<td><div class="summary">
Gets the current navigation entry of the content that is currently displayed.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal.navigationtarget(v=pandp.50)">NavigationTarget</a></td>
<td><div class="summary">
Gets or sets the target that implements INavigateAsync.
</div></td>
</tr>
</tbody>
</table>

See Also


[IRegionNavigationJournal Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationjournal(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
