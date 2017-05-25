---
TOCTitle: IRegionNavigationJournal Members
Title: 'IRegionNavigationJournal Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionNavigationJournal'
ms:mtpsurl: 'iregionnavigationjournal-members-mspp-regions.md'
---

Prism Class Library

IRegionNavigationJournal Members
================================

The [IRegionNavigationJournal](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.clear">Clear</a></td>
<td><div class="summary">
Clears the journal of current, back, and forward navigation histories.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.goback">GoBack</a></td>
<td><div class="summary">
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.goforward">GoForward</a></td>
<td><div class="summary">
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.recordnavigation(microsoft.practices.prism.regions.iregionnavigationjournalentry)">RecordNavigation</a></td>
<td><div class="summary">
Records the navigation to the entry..
</div></td>
</tr>
</tbody>
</table>

Properties
----------

<span id="propertyTableToggle"></span>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.cangoback">CanGoBack</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the back navigation history.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.cangoforward">CanGoForward</a></td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the forward navigation history.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.currententry">CurrentEntry</a></td>
<td><div class="summary">
Gets the current navigation entry of the content that is currently displayed.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405482.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal.navigationtarget">NavigationTarget</a></td>
<td><div class="summary">
Gets or sets the target that implements INavigateAsync.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[IRegionNavigationJournal Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationjournal)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
