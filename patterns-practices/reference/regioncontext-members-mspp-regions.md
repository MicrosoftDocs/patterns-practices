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

<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regioncontext-getobservablecontext-method-mspp-regions" data-raw-source="[GetObservableContext](/patterns-practices/reference/regioncontext-getobservablecontext-method-mspp-regions)">GetObservableContext</a></td>

<td><div class="summary">
Returns an <a href="/patterns-practices/reference/observableobject-t-class-mspp" data-raw-source="[ObservableObject&amp;lt;T&amp;gt;](/patterns-practices/reference/observableobject-t-class-mspp)">ObservableObject&lt;T&gt;</a> wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the <a href="/patterns-practices/reference/iregion-views-property-mspp-regions" data-raw-source="[Views](/patterns-practices/reference/iregion-views-property-mspp-regions)">Views</a> collection by the <a href="/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors" data-raw-source="[BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors)">BindRegionContextToDependencyObjectBehavior</a> Behavior. The RegionContext will also be set to the control that hosts the Region, by the <a href="/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors" data-raw-source="[SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors)">SyncRegionContextWithHostBehavior</a> Behavior. If the <a href="/patterns-practices/reference/observableobject-t-class-mspp" data-raw-source="[ObservableObject&amp;lt;T&amp;gt;](/patterns-practices/reference/observableobject-t-class-mspp)">ObservableObject&lt;T&gt;</a> wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionContext Class](/patterns-practices/reference/regioncontext-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)