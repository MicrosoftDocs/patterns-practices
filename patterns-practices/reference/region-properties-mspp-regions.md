---
TOCTitle: Region Properties
Title: 'Region Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.Region'
ms:mtpsurl: 'region-properties-mspp-regions.md'
---

# Region Properties

The [Region](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region) type exposes the following members.

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
<td>[ActiveViews](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.activeviews)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.behaviors)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.context)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ItemMetadataCollection](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.itemmetadatacollection)</td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.name)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager).
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.navigationservice)</td>
<td><div class="summary">
Gets the navigation service.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.regionmanager)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.sortcomparison)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.views)</td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div></td>
</tr>
</tbody>
</table>

## See Also
[Region Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
