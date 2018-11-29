---
TOCTitle: IRegion Properties
Title: 'IRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'iregion-properties-mspp-regions.md'
---

# IRegion Properties

The [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) type exposes the following members.

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
<td><a href="/patterns-practices/reference/iregion-activeviews-property-mspp-regions" data-raw-source="[ActiveViews](/patterns-practices/reference/iregion-activeviews-property-mspp-regions)">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-behaviors-property-mspp-regions" data-raw-source="[Behaviors](/patterns-practices/reference/iregion-behaviors-property-mspp-regions)">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a>s that can extend the behavior of regions.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-context-property-mspp-regions" data-raw-source="[Context](/patterns-practices/reference/iregion-context-property-mspp-regions)">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-name-property-mspp-regions" data-raw-source="[Name](/patterns-practices/reference/iregion-name-property-mspp-regions)">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-navigationservice-property-mspp-regions" data-raw-source="[NavigationService](/patterns-practices/reference/iregion-navigationservice-property-mspp-regions)">NavigationService</a></td>
<td><div class="summary">
Gets or sets the navigation service.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-regionmanager-property-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/iregion-regionmanager-property-mspp-regions)">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as <strong>truetrue</strong> (<strong>True</strong> in Visual Basic).
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-sortcomparison-property-mspp-regions" data-raw-source="[SortComparison](/patterns-practices/reference/iregion-sortcomparison-property-mspp-regions)">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/iregion-views-property-mspp-regions" data-raw-source="[Views](/patterns-practices/reference/iregion-views-property-mspp-regions)">Views</a></td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegion Interface](/patterns-practices/reference/iregion-interface-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  