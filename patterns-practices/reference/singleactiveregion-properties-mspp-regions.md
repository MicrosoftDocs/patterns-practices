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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.activeviews" data-raw-source="[ActiveViews](/patterns-practices/reference/region-class-mspp-regions.activeviews)">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.behaviors" data-raw-source="[Behaviors](/patterns-practices/reference/region-class-mspp-regions.behaviors)">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionBehavior</a>s that can extend the behavior of regions.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.context" data-raw-source="[Context](/patterns-practices/reference/region-class-mspp-regions.context)">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.itemmetadatacollection" data-raw-source="[ItemMetadataCollection](/patterns-practices/reference/region-class-mspp-regions.itemmetadatacollection)">ItemMetadataCollection</a></td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.name" data-raw-source="[Name](/patterns-practices/reference/region-class-mspp-regions.name)">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.navigationservice" data-raw-source="[NavigationService](/patterns-practices/reference/region-class-mspp-regions.navigationservice)">NavigationService</a></td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.regionmanager" data-raw-source="[RegionManager](/patterns-practices/reference/region-class-mspp-regions.regionmanager)">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <strong>truetrue</strong> (<strong>True</strong> in Visual Basic).
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.sortcomparison" data-raw-source="[SortComparison](/patterns-practices/reference/region-class-mspp-regions.sortcomparison)">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-class-mspp-regions.views" data-raw-source="[Views](/patterns-practices/reference/region-class-mspp-regions.views)">Views</a></td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[SingleActiveRegion Class](/patterns-practices/reference/singleactiveregion-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
