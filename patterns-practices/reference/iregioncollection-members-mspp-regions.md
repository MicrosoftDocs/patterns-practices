---
TOCTitle: IRegionCollection Members
Title: 'IRegionCollection Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionCollection'
ms:mtpsurl: 'iregioncollection-members-mspp-regions.md'
---

# IRegionCollection Members

The [IRegionCollection](/patterns-practices/reference/iregioncollection-interface-mspp-regions) type exposes the following members.

## Methods


<table style="width:100%;">

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
<td>[Add](/patterns-practices/reference/iregioncollection-add-method-mspp-regions
)</td>
<td><div class="summary">
Adds a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
) to the collection.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ContainsRegionWithName](/patterns-practices/reference/iregioncollection-containsregionwithname-method-mspp-regions
)</td>
<td><div class="summary">
Checks if the collection contains a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
) with the name received as parameter.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetEnumerator()](http://msdn.microsoft.com/en-us/library/s793z9y2)</td>
<td><div class="summary">
Returns an enumerator that iterates through the collection.
</div>
(Inherited from [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)&lt;[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)&gt;.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetEnumerator()](http://msdn.microsoft.com/en-us/library/5zae5365)</td>
<td><div class="summary">
Returns an enumerator that iterates through a collection.
</div>
(Inherited from [IEnumerable](http://msdn.microsoft.com/en-us/library/h1x9x1b1).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Remove](/patterns-practices/reference/iregioncollection-remove-method-mspp-regions
)</td>
<td><div class="summary">
Removes a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
) from the collection.
</div></td>
</tr>
</tbody>
</table>

## Extension Methods


<table style="width:100%;">

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
<td>[Add](/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions
)</td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
).)</td>
</tr>
</tbody>
</table>

## Properties


<table style="width:100%;">

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
<td>[Item](/patterns-practices/reference/iregioncollection-item-property-mspp-regions
)</td>
<td><div class="summary">
Gets the IRegion with the name received as index.
</div></td>
</tr>
</tbody>
</table>

## Events


<table style="width:100%;">

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
<td>[CollectionChanged](http://msdn.microsoft.com/en-us/library/ms653382)</td>
<td><div class="summary">
Occurs when the collection changes.
</div>
(Inherited from [INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629).)</td>
</tr>
</tbody>
</table>

## See Also

[IRegionCollection Interface](/patterns-practices/reference/iregioncollection-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)