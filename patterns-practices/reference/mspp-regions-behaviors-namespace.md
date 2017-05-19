---
TOCTitle: 'Microsoft.Practices.Prism.Regions.Behaviors Namespace'
Title: 'Microsoft.Practices.Prism.Regions.Behaviors Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.Regions.Behaviors'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419045(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.Regions.Behaviors Namespace
=====================================================

 

Classes
-------

<span id="classToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.autopopulateregionbehavior">AutoPopulateRegionBehavior</a></td>
<td><div class="summary">
Populates the target region with the views registered to it in the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionviewregistry">IRegionViewRegistry</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.bindregioncontexttodependencyobjectbehavior">BindRegionContextToDependencyObjectBehavior</a></td>
<td><div class="summary">
Defines a behavior that forwards the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty">RegionContextProperty</a> to the views in the region.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.clearchildviewsregionbehavior">ClearChildViewsRegionBehavior</a></td>
<td><div class="summary">
Behavior that removes the RegionManager attached property of all the views in a region once the RegionManager property of a region becomes null. This is useful when removing views with nested regions, to ensure these nested regions get removed from the RegionManager as well.
<div>
<h2 id="remarks">Remarks</h2>
<span id="remarksToggle"></span> This behavior does not apply by default. In order to activate it, the ClearChildViews attached property must be set to True in the view containing the affected child regions.
</div>
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior">DelayedRegionCreationBehavior</a></td>
<td><div class="summary">
Behavior that creates a new <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a>, when the control that will host the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> (see <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement">TargetElement</a>) is added to the VisualTree. This behavior will use the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadaptermappings">RegionAdapterMappings</a> class to find the right type of adapter to create the region. After the region is created, this behavior will detach.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionactiveawarebehavior">RegionActiveAwareBehavior</a></td>
<td><div class="summary">
Behavior that monitors a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> object and changes the value for the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.iactiveaware.isactive">IsActive</a> property when an object that implements <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.iactiveaware">IActiveAware</a> gets added or removed from the collection.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regioncreationexception">RegionCreationException</a></td>
<td><div class="summary">
Represents errors that occured during region creation.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior">RegionManagerRegistrationBehavior</a></td>
<td><div class="summary">
Subscribes to a static event from the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager">RegionManager</a> in order to register the target <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> in a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager">IRegionManager</a> when one is available on the host control by walking up the tree and finding a control whose <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regionmanagerproperty">RegionManagerProperty</a> property is not nullNothingnullptra null reference (Nothing in Visual Basic).
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmemberlifetimebehavior">RegionMemberLifetimeBehavior</a></td>
<td><div class="summary">
The RegionMemberLifetimeBehavior determines if items should be removed from the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> when they are deactivated.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.selectoritemssourcesyncbehavior">SelectorItemsSourceSyncBehavior</a></td>
<td><div class="summary">
Defines the attached behavior that keeps the items of the <a href="http://msdn2.microsoft.com/en-us/library/ms595227">Selector</a> host control in synchronization with the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a>. This behavior also makes sure that, if you activate a view in a region, the SelectedItem is set. If you set the SelectedItem or SelectedItems (ListBox) then this behavior will also call Activate on the selected items.
<div>
<h2 id="remarks-1">Remarks</h2>
<span id="remarksToggle"></span> When calling Activate on a view, you can only select a single active view at a time. By setting the SelectedItems property of a listbox, you can set multiple views to active.
</div>
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.syncregioncontextwithhostbehavior">SyncRegionContextWithHostBehavior</a></td>
<td><div class="summary">
Behavior that synchronizes the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.context">Context</a> property of a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> with the control that hosts the Region. It does this by setting the <a href="https://msdn.microsoft.com/f:microsoft.practices.prism.regions.regionmanager.regioncontextproperty">RegionContextProperty</a> Dependency Property on the host control. This behavior allows the usage of two way databinding of the RegionContext from XAML.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg419045.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.ihostawareregionbehavior">IHostAwareRegionBehavior</a></td>
<td><div class="summary">
Defines a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior">IRegionBehavior</a> that not allows extensible behaviors on regions which also interact with the target element that the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion">IRegion</a> is attached to.
</div></td>
</tr>
</tbody>
</table>
