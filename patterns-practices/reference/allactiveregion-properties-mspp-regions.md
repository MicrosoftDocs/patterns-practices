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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/allactiveregion-activeviews-property-mspp-regions" data-raw-source="[ActiveViews](/patterns-practices/reference/allactiveregion-activeviews-property-mspp-regions)">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region. These are all the added views.
</div>
(Overrides <a href="/patterns-practices/reference/region-activeviews-property-mspp-regions" data-raw-source="[Region.ActiveViews](/patterns-practices/reference/region-activeviews-property-mspp-regions)">Region.ActiveViews</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-behaviors-property-mspp-regions" data-raw-source="[Behaviors](/patterns-practices/reference/region-behaviors-property-mspp-regions)">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a>s that can extend the behavior of regions.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-context-property-mspp-regions" data-raw-source="[Context](/patterns-practices/reference/region-context-property-mspp-regions)">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protproperty.gif" alt="Protected property"/></td>
<td><a href="/patterns-practices/reference/region-itemmetadatacollection-property-mspp-regions" data-raw-source="[ItemMetadataCollection](/patterns-practices/reference/region-itemmetadatacollection-property-mspp-regions)">ItemMetadataCollection</a></td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-name-property-mspp-regions" data-raw-source="[Name](/patterns-practices/reference/region-name-property-mspp-regions)">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-navigationservice-property-mspp-regions" data-raw-source="[NavigationService](/patterns-practices/reference/region-navigationservice-property-mspp-regions)">NavigationService</a></td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-regionmanager-property-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/region-regionmanager-property-mspp-regions)">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <strong>Truetrue</strong> (<strong>True</strong> in Visual Basic).
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-sortcomparison-property-mspp-regions" data-raw-source="[SortComparison](/patterns-practices/reference/region-sortcomparison-property-mspp-regions)">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/region-views-property-mspp-regions" data-raw-source="[Views](/patterns-practices/reference/region-views-property-mspp-regions)">Views</a></td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from <a href="/patterns-practices/reference/region-class-mspp-regions" data-raw-source="[Region](/patterns-practices/reference/region-class-mspp-regions)">Region</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[AllActiveRegion Class](/patterns-practices/reference/allactiveregion-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  
