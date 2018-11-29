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
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/autopopulateregionbehavior-class-mspp-regions-behaviors" data-raw-source="[AutoPopulateRegionBehavior](/patterns-practices/reference/autopopulateregionbehavior-class-mspp-regions-behaviors)">AutoPopulateRegionBehavior</a></td>
<td><div class="summary">
Populates the target region with the views registered to it in the <a href="/patterns-practices/reference/iregionviewregistry-interface-mspp-regions" data-raw-source="[IRegionViewRegistry](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)">IRegionViewRegistry</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors" data-raw-source="[BindRegionContextToDependencyObjectBehavior](/patterns-practices/reference/bindregioncontexttodependencyobjectbehavior-class-mspp-regions-behaviors)">BindRegionContextToDependencyObjectBehavior</a></td>
<td><div class="summary">
Defines a behavior that forwards the <a href="/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions" data-raw-source="[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)">RegionContextProperty</a> to the views in the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/clearchildviewsregionbehavior-class-mspp-regions-behaviors" data-raw-source="[ClearChildViewsRegionBehavior](/patterns-practices/reference/clearchildviewsregionbehavior-class-mspp-regions-behaviors)">ClearChildViewsRegionBehavior</a></td>
<td><div class="summary">
Behavior that removes the RegionManager attached property of all the views in a region once the RegionManager property of a region becomes null. This is useful when removing views with nested regions, to ensure these nested regions get removed from the RegionManager as well.
<div>
<h2 id="remarks">Remarks</h2>
 This behavior does not apply by default. In order to activate it, the ClearChildViews attached property must be set to True in the view containing the affected child regions.
</div>
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors" data-raw-source="[DelayedRegionCreationBehavior](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)">DelayedRegionCreationBehavior</a></td>
<td><div class="summary">
Behavior that creates a new <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>, when the control that will host the <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> (see <a href="/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors" data-raw-source="[TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)">TargetElement</a>) is added to the VisualTree. This behavior will use the <a href="/patterns-practices/reference/regionadaptermappings-class-mspp-regions" data-raw-source="[RegionAdapterMappings](/patterns-practices/reference/regionadaptermappings-class-mspp-regions)">RegionAdapterMappings</a> class to find the right type of adapter to create the region. After the region is created, this behavior will detach.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionactiveawarebehavior-class-mspp-regions-behaviors" data-raw-source="[RegionActiveAwareBehavior](/patterns-practices/reference/regionactiveawarebehavior-class-mspp-regions-behaviors)">RegionActiveAwareBehavior</a></td>
<td><div class="summary">
Behavior that monitors a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> object and changes the value for the <a href="/patterns-practices/reference/iactiveaware-isactive-property-mspp" data-raw-source="[IsActive](/patterns-practices/reference/iactiveaware-isactive-property-mspp)">IsActive</a> property when an object that implements <a href="/patterns-practices/reference/iactiveaware-interface-mspp" data-raw-source="[IActiveAware](/patterns-practices/reference/iactiveaware-interface-mspp)">IActiveAware</a> gets added or removed from the collection.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors" data-raw-source="[RegionCreationException](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors)">RegionCreationException</a></td>
<td><div class="summary">
Represents errors that occured during region creation.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors" data-raw-source="[RegionManagerRegistrationBehavior](/patterns-practices/reference/regionmanagerregistrationbehavior-class-mspp-regions-behaviors)">RegionManagerRegistrationBehavior</a></td>
<td><div class="summary">
Subscribes to a static event from the <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a> in order to register the target <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> in a <a href="/patterns-practices/reference/iregionmanager-interface-mspp-regions" data-raw-source="[IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions)">IRegionManager</a> when one is available on the host control by walking up the tree and finding a control whose <a href="/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions" data-raw-source="[RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions)">RegionManagerProperty</a> property is not <strong>null</strong>a null reference (<strong>Nothing</strong> in Visual Basic).
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors" data-raw-source="[RegionMemberLifetimeBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)">RegionMemberLifetimeBehavior</a></td>
<td><div class="summary">
The RegionMemberLifetimeBehavior determines if items should be removed from the <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> when they are deactivated.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors" data-raw-source="[SelectorItemsSourceSyncBehavior](/patterns-practices/reference/regionmemberlifetimebehavior-class-mspp-regions-behaviors)">SelectorItemsSourceSyncBehavior</a></td>
<td><div class="summary">
Defines the attached behavior that keeps the items of the <a href="http://msdn.microsoft.com/en-us/library/ms595227" data-raw-source="[Selector](http://msdn.microsoft.com/en-us/library/ms595227)">Selector</a> host control in synchronization with the <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>. This behavior also makes sure that, if you activate a view in a region, the SelectedItem is set. If you set the SelectedItem or SelectedItems (ListBox) then this behavior will also call Activate on the selected items.
<div>
<h2 id="remarks-1">Remarks</h2>
 When calling Activate on a view, you can only select a single active view at a time. By setting the SelectedItems property of a listbox, you can set multiple views to active.
</div>
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors" data-raw-source="[SyncRegionContextWithHostBehavior](/patterns-practices/reference/syncregioncontextwithhostbehavior-class-mspp-regions-behaviors)">SyncRegionContextWithHostBehavior</a></td>
<td><div class="summary">
Behavior that synchronizes the <a href="/patterns-practices/reference/iregion-context-property-mspp-regions" data-raw-source="[Context](/patterns-practices/reference/iregion-context-property-mspp-regions)">Context</a> property of a <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> with the control that hosts the Region. It does this by setting the <a href="/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions" data-raw-source="[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)">RegionContextProperty</a> Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.
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
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/ihostawareregionbehavior-interface-mspp-regions-behaviors" data-raw-source="[IHostAwareRegionBehavior](/patterns-practices/reference/ihostawareregionbehavior-interface-mspp-regions-behaviors)">IHostAwareRegionBehavior</a></td>
<td><div class="summary">
Defines a <a href="/patterns-practices/reference/iregionbehavior-interface-mspp-regions" data-raw-source="[IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)">IRegionBehavior</a> that not allows extensible behaviors on regions which also interact with the target element that the <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> is attached to.
</div></td>
</tr>
</tbody>
</table>
