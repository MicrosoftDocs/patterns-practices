---
TOCTitle: IRegionViewRegistry Members
Title: 'IRegionViewRegistry Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionViewRegistry'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405488(v=PandP.50)'
---

Prism Class Library

IRegionViewRegistry Members
===========================


The [IRegionViewRegistry](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionviewregistry) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg405488.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionviewregistry.getcontents(system.string)">GetContents</a></td>
<td><div class="summary">
Returns the contents associated with a region name.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg405488.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionviewregistry.registerviewwithregion(system.string%2csystem.func%7bsystem.object%7d)">RegisterViewWithRegion(String, Func&lt;(Of &lt;(Object&gt;)&gt;))</a></td>
<td><div class="summary">
Registers a delegate that can be used to retrieve the content associated with a region name.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg405488.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregionviewregistry.registerviewwithregion(system.string%2csystem.type)">RegisterViewWithRegion(String, Type)</a></td>
<td><div class="summary">
Registers a content type with a region name.
</div></td>
</tr>
</tbody>
</table>

Events
------

<span id="eventTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg405488.pubevent(en-us,PandP.50).gif" title="Public event" /></td>
<td><a href="https://msdn.microsoft.com/e:microsoft.practices.prism.regions.iregionviewregistry.contentregistered">ContentRegistered</a></td>
<td><div class="summary">
Event triggered when a content is registered to a region name.
</div></td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegionViewRegistry Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionviewregistry)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
