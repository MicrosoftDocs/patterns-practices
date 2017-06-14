---
TOCTitle: RegionContext Methods
Title: 'RegionContext Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.RegionContext'
ms:mtpsurl: 'regioncontext-methods-mspp-regions.md'
---

# RegionContext Methods

The [RegionContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext) type exposes the following members.

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
<td>[GetObservableContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext.getobservablecontext(system.windows.dependencyobject))</td>
<td><div class="summary">
Returns an [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper around the RegionContext value. The RegionContext will be set on any views (dependency objects) that are inside the [Views](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.views) collection by the [BindRegionContextToDependencyObjectBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior) Behavior. The RegionContext will also be set to the control that hosts the Region, by the [SyncRegionContextWithHostBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior) Behavior. If the [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not already exist, an empty one will be created. This way, an observer can notify when the value is set for the first time.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionContext Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regioncontext)  
[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)