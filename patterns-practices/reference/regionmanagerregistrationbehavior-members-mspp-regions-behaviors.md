---
TOCTitle: RegionManagerRegistrationBehavior Members
Title: 'RegionManagerRegistrationBehavior Members (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.Behaviors.RegionManagerRegistrationBehavior'
ms:mtpsurl: 'regionmanagerregistrationbehavior-members-mspp-regions-behaviors.md'
---

# RegionManagerRegistrationBehavior Members

The [RegionManagerRegistrationBehavior](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors) type exposes the following members.

## Constructors

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>RegionManagerRegistrationBehavior</td>
<td><div class="summary">
Initializes a new instance of [RegionManagerRegistrationBehavior](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors).
</div></td>
</tr>
</tbody>
</table>

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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Attach](/patterns-practices/reference/regionbehavior-attach-method-mspp-regions)</td>
<td><div class="summary">
Attaches the behavior to the region.
</div>
(Inherited from [RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[OnAttach](/patterns-practices/reference/regionmanagerregistrationbehavior-onattach-method-mspp-regions-behaviors)</td>
<td><div class="summary">
When the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) has a name assigned, the behavior will start monitoring the ancestor controls in the element tree to look for an [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) where to register the region in.
</div>
(Overrides [RegionBehavior.OnAttach()](/patterns-practices/reference/regionbehavior-onattach-method-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[OnUpdatingRegions](/patterns-practices/reference/regionmanagerregistrationbehavior-onupdatingregions-method-mspp-regions-behaviors)</td>
<td><div class="summary">
This event handler gets called when a RegionManager is requering the instances of a region to be registered if they are not already.
<div>
<h3 id="remarks">Remarks</h3>
Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.
</div>
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## Fields

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
<td>![Public field](/patterns-practices/reference/images/public-field.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[BehaviorKey](/patterns-practices/reference/regionmanagerregistrationbehavior-behaviorkey-field-mspp-regions-behaviors)</td>
<td><div class="summary">
The key of this behavior.
</div></td>
</tr>
</tbody>
</table>

## Properties

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
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[HostControl](/patterns-practices/reference/regionmanagerregistrationbehavior-hostcontrol-property-mspp-regions-behaviors)</td>
<td><div class="summary">
Gets or sets the [DependencyObject](http://msdn.microsoft.com/en-us/library/ms589309) that the [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) is attached to.
</div></td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[IsAttached](/patterns-practices/reference/regionbehavior-isattached-property-mspp-regions)</td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if the behavior is attached to a region, falseFalsefalsefalse (False in Visual Basic) otherwise.
</div>
(Inherited from [RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Region](/patterns-practices/reference/regionbehavior-region-property-mspp-regions)</td>
<td><div class="summary">
Behavior's attached region.
</div>
(Inherited from [RegionBehavior](/patterns-practices/reference/regionbehavior-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManagerAccessor](/patterns-practices/reference/regionmanagerregistrationbehavior-regionmanageraccessor-property-mspp-regions-behaviors)</td>
<td><div class="summary">
Provides an abstraction on top of the RegionManager static members.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManagerRegistrationBehavior Class](/patterns-practices/reference/regioncreationexception-class-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  