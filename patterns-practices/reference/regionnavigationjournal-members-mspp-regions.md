---
TOCTitle: RegionNavigationJournal Members
Title: 'RegionNavigationJournal Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionNavigationJournal'
ms:mtpsurl: 'regionnavigationjournal-members-mspp-regions.md'
---


# RegionNavigationJournal Members

The [RegionNavigationJournal](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions) type exposes the following members.

## Constructors


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
<td>RegionNavigationJournal</td>
<td><div class="summary">
Initializes a new instance of the [RegionNavigationJournal](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions) class
</div></td>
</tr>
</tbody>
</table>

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
<td>[Clear](/patterns-practices/reference/regionnavigationjournal-clear-method-mspp-regions)</td>
<td><div class="summary">
Clears the journal of current, back, and forward navigation histories.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GoBack](/patterns-practices/reference/regionnavigationjournal-goback-method-mspp-regions)</td>
<td><div class="summary">
Navigates to the most recent entry in the back navigation history, or does nothing if no entry exists in back navigation.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GoForward](/patterns-practices/reference/regionnavigationjournal-goforward-method-mspp-regions)</td>
<td><div class="summary">
Navigates to the most recent entry in the forward navigation history, or does nothing if no entry exists in forward navigation.
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RecordNavigation](/patterns-practices/reference/regionnavigationjournal-recordnavigation-method-mspp-regions)</td>
<td><div class="summary">
Records the navigation to the entry..
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
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
<td>[CanGoBack](/patterns-practices/reference/regionnavigationjournal-cangoback-property-mspp-regions)</td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the back navigation history.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CanGoForward](/patterns-practices/reference/regionnavigationjournal-cangoforward-property-mspp-regions)</td>
<td><div class="summary">
Gets a value that indicates whether there is at least one entry in the forward navigation history.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[CurrentEntry](/patterns-practices/reference/regionnavigationjournal-currententry-property-mspp-regions)</td>
<td><div class="summary">
Gets the current navigation entry of the content that is currently displayed.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationTarget](/patterns-practices/reference/regionnavigationjournal-navigationtarget-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the target that implements INavigate.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionNavigationJournal Class](/patterns-practices/reference/regionnavigationjournal-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)