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
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(IRegionManager, String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)![Static member](/images/static.gif)</td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
</tbody>
</table>

## See Also
[RegionManagerExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
