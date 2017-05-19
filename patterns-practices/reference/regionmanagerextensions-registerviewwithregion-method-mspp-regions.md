---
TOCTitle: RegisterViewWithRegion Method
Title: 'RegionManagerExtensions.RegisterViewWithRegion Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RegisterViewWithRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419137(v=PandP.50)'
---

Prism Class Library

RegionManagerExtensions..::.RegisterViewWithRegion Method
=========================================================


Overload List
-------------

<span id="overloadMembersTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419137.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg419137.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(IRegionManager, String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td><div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419137.pubmethod(en-us,PandP.50).gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg419137.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionmanagerextensions.registerviewwithregion(microsoft.practices.prism.regions.iregionmanager%2csystem.string%2csystem.type)">RegisterViewWithRegion(IRegionManager, String, Type)</a></td>
<td><div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div></td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionManagerExtensions Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanagerextensions)

[RegionManagerExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanagerextensions)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
