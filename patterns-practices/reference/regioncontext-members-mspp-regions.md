---
TOCTitle: RegionContext Members
Title: 'RegionContext Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionContext'
ms:mtpsurl: 'regioncontext-members-mspp-regions.md'
---

# RegionContext Members

The [RegionContext](/patterns-practices/reference/regioncontext-class-mspp-regions) type exposes the following members.

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

<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetObservableContext](/patterns-practices/reference/regioncontext-getobservablecontext-method-mspp-regions)</td>

<td><div class="summary">
Returns an [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](/patterns-practices/reference/iregion-views-property-mspp-regions) collection by the [BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors) Behavior. If the [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionContext Class](/patterns-practices/reference/regioncontext-class-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)