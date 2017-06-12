---
TOCTitle: 'Microsoft.Practices.Prism.Regions.Behaviors Namespace'
Title: 'Microsoft.Practices.Prism.Regions.Behaviors Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Regions.Behaviors'
ms:mtpsurl: 'mspp-regions-behaviors-namespace.md'
---


# Microsoft.Practices.Prism.Regions.Behaviors Namespace

 

## Classes


<table>

<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[AutoPopulateRegionBehavior](/patterns-practices/reference/autopopulateregionbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Populates the target region with the views registered to it in the [IRegionViewRegistry](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Defines a behavior that forwards the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) to the views in the region.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[ClearChildViewsRegionBehavior](/patterns-practices/reference/clearchildviewsregionbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Behavior that removes the RegionManager attached property of all the views in a region once the RegionManager property of a region becomes null. This is useful when removing views with nested regions, to ensure these nested regions get removed from the RegionManager as well.
<div>
<h2 id="remarks">Remarks</h2>
 This behavior does not apply by default. In order to activate it, the ClearChildViews attached property must be set to True in the view containing the affected child regions.
</div>
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[DelayedRegionCreationBehavior](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Behavior that creates a new [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions), when the control that will host the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) (see [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)) is added to the VisualTree. This behavior will use the [RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions) class to find the right type of adapter to create the region. After the region is created, this behavior will detach.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionActiveAwareBehavior](/patterns-practices/reference/regionactiveawarebehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Behavior that monitors a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) object and changes the value for the [IsActive](/patterns-practices/reference/iactiveaware-isactive-property-mspp) property when an object that implements [IActiveAware](/patterns-practices/reference/iactiveaware-interface-mspp) gets added or removed from the collection.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionCreationException](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Represents errors that occured during region creation.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionManagerRegistrationBehavior](/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Subscribes to a static event from the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) in order to register the target [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) in a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) when one is available on the host control by walking up the tree and finding a control whose [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) property is not **null**a null reference (**Nothing** in Visual Basic).
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
The RegionMemberLifetimeBehavior determines if items should be removed from the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) when they are deactivated.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[SelectorItemsSourceSyncBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Defines the attached behavior that keeps the items of the [Selector](http://msdn.microsoft.com/en-us/library/ms595227) host control in synchronization with the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions). This behavior also makes sure that, if you activate a view in a region, the SelectedItem is set. If you set the SelectedItem or SelectedItems (ListBox) then this behavior will also call Activate on the selected items.
<div>
<h2 id="remarks-1">Remarks</h2>
 When calling Activate on a view, you can only select a single active view at a time. By setting the SelectedItems property of a listbox, you can set multiple views to active.
</div>
</div></td>
</tr>
<tr class="even">
<td>![Public class](/patterns-practices/reference/images/public-class.gif)</td>
<td>[SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors)</td>
<td><div class="summary">
Behavior that synchronizes the [Context](/patterns-practices/reference/iregion-context-property-mspp-regions) property of a [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) with the control that hosts the Region. It does this by setting the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.
</div></td>
</tr>
</tbody>
</table>

## Interfaces


<table>

<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public interface](/patterns-practices/reference/images/public-interface.gif)</td>
<td>[IHostAwareRegionBehavior](/patterns-practices/reference/ihostawareregionbehavior-interface-mspp-regions-behaviors)</td>
<td><div class="summary">
Defines a [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions) that not allows extensible behaviors on regions which also interact with the target element that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.
</div></td>
</tr>
</tbody>
</table>
