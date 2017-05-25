---
TOCTitle: MefRegionManagerRegistrationBehavior Members
Title: 'MefRegionManagerRegistrationBehavior Members (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionManagerRegistrationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430806(v=PandP.50)'
---


# MefRegionManagerRegistrationBehavior Members

The [MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior) type exposes the following members.

## Constructors

<span id="constructorTableToggle"></span>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior.">MefRegionManagerRegistrationBehavior</a></td>
<td><div class="summary">
Initializes a new instance of the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior">MefRegionManagerRegistrationBehavior</a> class
</div></td>
</tr>
</tbody>
</table>

## Methods

<span id="methodTableToggle"></span>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior.attach">Attach</a></td>
<td><div class="summary">
Attaches the behavior to the region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior">RegionBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.onattach">OnAttach</a></td>
<td><div class="summary">
When the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> has a name assigned, the behavior will start monitoring the ancestor controls in the element tree to look for an <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionmanager">IRegionManager</a> where to register the region in.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior">RegionManagerRegistrationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.onupdatingregions(system.object%2csystem.eventargs)">OnUpdatingRegions</a></td>
<td><div class="summary">
This event handler gets called when a RegionManager is requering the instances of a region to be registered if they are not already.
<div>
<h2 id="remarks">Remarks</h2>
Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.
</div>
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior">RegionManagerRegistrationBehavior</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## Properties

<span id="propertyTableToggle"></span>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.hostcontrol">HostControl</a></td>
<td><div class="summary">
Gets or sets the <a href="http://msdn.microsoft.com/en-us/library/ms589309">DependencyObject</a> that the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion">IRegion</a> is attached to.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior">RegionManagerRegistrationBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior.isattached">IsAttached</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if the behavior is attached to a region, falseFalsefalsefalse (False in Visual Basic) otherwise.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior">RegionBehavior</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior.region">Region</a></td>
<td><div class="summary">
Behavior's attached region.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionbehavior">RegionBehavior</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif" title="Public property" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.regionmanageraccessor">RegionManagerAccessor</a></td>
<td><div class="summary">
Provides an abstraction on top of the RegionManager static members.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior">RegionManagerRegistrationBehavior</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[MefRegionManagerRegistrationBehavior Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.regions.behaviors)
