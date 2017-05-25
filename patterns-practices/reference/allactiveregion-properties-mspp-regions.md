---
TOCTitle: AllActiveRegion Properties
Title: 'AllActiveRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.AllActiveRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431183(v=PandP.50)'
---


# AllActiveRegion Properties

The [AllActiveRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.allactiveregion) type exposes the following members.

## Properties

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
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.allactiveregion.activeviews">ActiveViews</a></td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region. These are all the added views.
</div>
(Overrides <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.activeviews">Region.ActiveViews</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.behaviors">Behaviors</a></td>
<td><div class="summary">
Gets the collection of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a>s that can extend the behavior of regions.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.context">Context</a></td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.protproperty(en-us,PandP.50).gif" title="Protected property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.itemmetadatacollection">ItemMetadataCollection</a></td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.name">Name</a></td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.navigationservice">NavigationService</a></td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.regionmanager">RegionManager</a></td>
<td><div class="summary">
Gets or sets the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a> that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.sortcomparison">SortComparison</a></td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region.views">Views</a></td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.region">Region</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[AllActiveRegion Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.allactiveregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
