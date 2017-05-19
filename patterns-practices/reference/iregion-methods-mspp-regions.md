---
TOCTitle: IRegion Methods
Title: 'IRegion Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431084(v=PandP.50)'
---

Prism Class Library

IRegion Methods
===============

The [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) type exposes the following members.

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
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.activate(system.object)">Activate</a></td>
<td><div class="summary">
Marks the specified view as active.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object)">Add(Object)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string)">Add(Object, String)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean)">Add(Object, String, Boolean)</a></td>
<td><div class="summary">
Adds a new view to the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.deactivate(system.object)">Deactivate</a></td>
<td><div class="summary">
Marks the specified view as inactive.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.getview(system.string)">GetView</a></td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.remove(system.object)">Remove</a></td>
<td><div class="summary">
Removes the specified view from the region.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn2.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td><div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn2.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync">INavigateAsync</a>.)</td>
</tr>
</tbody>
</table>

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string)">RequestNavigate(String)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri)">RequestNavigate(Uri)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the <a href="http://msdn2.microsoft.com/en-us/library/txt7706a">Uri</a>.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d)">RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg431084.pubextension(en-us,PandP.50).gif" title="Public Extension Method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters)">RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
Initiates navigation to the target specified by the target.
</div>
(Defined by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions">NavigationAsyncExtensions</a>.)</td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegion Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
