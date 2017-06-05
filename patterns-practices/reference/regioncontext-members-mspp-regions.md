---
TOCTitle: RegionContext Members
Title: 'RegionContext Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionContext'
ms:mtpsurl: 'regioncontext-members-mspp-regions.md'
---

# RegionContext Members

The [RegionContext](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regioncontext(v=pandp.50)) type exposes the following members.

## Methods


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

<td><img src="images/public-method.gif" title="Public method" /><img src="https://msdn.microsoft.com/en-us/Gg405506.static(en-us,PandP.50).gif" title="Static member" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regioncontext.getobservablecontext(v=pandp.50)">GetObservableContext</a></td>

<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static.gif)</td>
<td><a href="/patterns-practices/reference/mspp-regions-namespace.regioncontext.getobservablecontext(system.windows.dependencyobject)">GetObservableContext</a></td>

<td><div class="summary">
Returns an <a href="https://msdn.microsoft.com/en-us/library/gg431509(v=pandp.50)">ObservableObject&lt;T&gt;</a> wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion.views(v=pandp.50)">Views</a> collection by the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior(v=pandp.50)">BindRegionContextToDependencyObjectBehavior</a> Behavior. The RegionContext will also be set to the control that hosts the Region, by the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior(v=pandp.50)">SyncRegionContextWithHostBehavior</a> Behavior. If the <a href="https://msdn.microsoft.com/en-us/library/gg431509(v=pandp.50)">ObservableObject&lt;T&gt;</a> wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionContext Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regioncontext(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
