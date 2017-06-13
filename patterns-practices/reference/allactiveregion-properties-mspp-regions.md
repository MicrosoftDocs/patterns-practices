---
TOCTitle: AllActiveRegion Properties
Title: 'AllActiveRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.AllActiveRegion'
ms:mtpsurl: 'allactiveregion-properties-mspp-regions.md'
---


# AllActiveRegion Properties

The [AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions) type exposes the following members.

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
<td>[ActiveViews](/patterns-practices/reference/allactiveregion-activeviews-property-mspp-regions)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region. These are all the added views.
</div>
(Overrides [Region.ActiveViews](/patterns-practices/reference/region-activeviews-property-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](/patterns-practices/reference/region-behaviors-property-mspp-regions)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)s that can extend the behavior of regions.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](/patterns-practices/reference/region-context-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ItemMetadataCollection](/patterns-practices/reference/region-itemmetadatacollection-property-mspp-regions)</td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](/patterns-practices/reference/region-name-property-mspp-regions)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](/patterns-practices/reference/region-navigationservice-property-mspp-regions)</td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](/patterns-practices/reference/region-regionmanager-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](/patterns-practices/reference/region-sortcomparison-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](/patterns-practices/reference/region-views-property-mspp-regions)</td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
</tbody>
</table>

## See Also

[AllActiveRegion Class](/patterns-practices/reference/allactiveregion-class-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>