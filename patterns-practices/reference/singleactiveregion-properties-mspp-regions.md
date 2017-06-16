---
TOCTitle: SingleActiveRegion Properties
Title: 'SingleActiveRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.SingleActiveRegion'
ms:mtpsurl: 'singleactiveregion-properties-mspp-regions.md'
---

# SingleActiveRegion Properties

The [SingleActiveRegion](/patterns-practices/reference/singleactiveregion-class-mspp-regions) type exposes the following members.

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
<td>[ActiveViews](/patterns-practices/reference/region-class-mspp-regions.activeviews)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](/patterns-practices/reference/region-class-mspp-regions.behaviors)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](/patterns-practices/reference/iregionmanager-interface-mspp-regions)s that can extend the behavior of regions.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](/patterns-practices/reference/region-class-mspp-regions.context)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ItemMetadataCollection](/patterns-practices/reference/region-class-mspp-regions.itemmetadatacollection)</td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](/patterns-practices/reference/region-class-mspp-regions.name)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](/patterns-practices/reference/region-class-mspp-regions.navigationservice)</td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](/patterns-practices/reference/region-class-mspp-regions.regionmanager)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](/patterns-practices/reference/region-class-mspp-regions.sortcomparison)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](/patterns-practices/reference/region-class-mspp-regions.views)</td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
</tbody>
</table>

## See Also

[SingleActiveRegion Class](/patterns-practices/reference/singleactiveregion-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
