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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregioncollection-add-method-mspp-regions" data-raw-source="[Add](/patterns-practices/reference/iregioncollection-add-method-mspp-regions
)">Add</a></td>
<td><div class="summary">
Adds a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)">IRegion</a> to the collection.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregioncollection-containsregionwithname-method-mspp-regions" data-raw-source="[ContainsRegionWithName](/patterns-practices/reference/iregioncollection-containsregionwithname-method-mspp-regions
)">ContainsRegionWithName</a></td>
<td><div class="summary">
Checks if the collection contains a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)">IRegion</a> with the name received as parameter.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/s793z9y2" data-raw-source="[GetEnumerator()](http://msdn.microsoft.com/en-us/library/s793z9y2)">GetEnumerator()</a></td>
<td><div class="summary">
Returns an enumerator that iterates through the collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/9eekhta0" data-raw-source="[IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)">IEnumerable</a>&lt;<a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)">IRegion</a>&gt;.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/5zae5365" data-raw-source="[GetEnumerator()](http://msdn.microsoft.com/en-us/library/5zae5365)">GetEnumerator()</a></td>
<td><div class="summary">
Returns an enumerator that iterates through a collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/h1x9x1b1" data-raw-source="[IEnumerable](http://msdn.microsoft.com/en-us/library/h1x9x1b1)">IEnumerable</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/iregioncollection-remove-method-mspp-regions" data-raw-source="[Remove](/patterns-practices/reference/iregioncollection-remove-method-mspp-regions
)">Remove</a></td>
<td><div class="summary">
Removes a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions
)">IRegion</a> from the collection.
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
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions" data-raw-source="[Add](/patterns-practices/reference/regionmanagerextensions-add-method-mspp-regions
)">Add</a></td>
<td><div class="summary">
Adds a region to the regionmanager with the name received as argument.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions
)">RegionManagerExtensions</a>.)</td>
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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregioncollection-item-property-mspp-regions" data-raw-source="[Item](/patterns-practices/reference/iregioncollection-item-property-mspp-regions
)">Item</a></td>
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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/ms653382" data-raw-source="[CollectionChanged](http://msdn.microsoft.com/en-us/library/ms653382)">CollectionChanged</a></td>
<td><div class="summary">
Occurs when the collection changes.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/ms668629" data-raw-source="[INotifyCollectionChanged](http://msdn.microsoft.com/en-us/library/ms668629)">INotifyCollectionChanged</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[IRegionCollection Interface](/patterns-practices/reference/iregioncollection-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)