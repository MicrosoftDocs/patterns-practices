---
TOCTitle: RegisterViewWithRegion Method
Title: 'RegionManagerExtensions.RegisterViewWithRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RegisterViewWithRegion'
ms:mtpsurl: 'regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions.md'
---


# RegionManagerExtensions.RegisterViewWithRegion Method

## Overload List


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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions
">RegisterViewWithRegion(IRegionManager, String, Func(Of Object))</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static.gif)</td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions
">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerExtensions Class](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)

[RegionManagerExtensions Members](/patterns-practices/reference/regionmanagerextensions-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
