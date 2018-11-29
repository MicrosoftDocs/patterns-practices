---
TOCTitle: DelayedRegionCreationBehavior Members
Title: 'DelayedRegionCreationBehavior Members (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior'
ms:mtpsurl: 'delayedregioncreationbehavior-members-mspp-regions-behaviors.md'
---

# DelayedRegionCreationBehavior Members

The [DelayedRegionCreationBehavior](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>DelayedRegionCreationBehavior</td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors" data-raw-source="[DelayedRegionCreationBehavior](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)">DelayedRegionCreationBehavior</a> class.
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/regionbehavior-attach-method-mspp-regions" data-raw-source="[Attach](/patterns-practices/reference/regionbehavior-attach-method-mspp-regions)">Attach</a></td>
<td><div class="summary">
Start monitoring the <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a> and the <a href="/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors" data-raw-source="[TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)">TargetElement</a> to detect when the <a href="/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors" data-raw-source="[TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)">TargetElement</a> becomes part of the Visual Tree. When that happens, the Region will be created and the behavior will <a href="/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors" data-raw-source="[Detach](/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors)">Detach</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-createregion-method-mspp-regions-behaviors" data-raw-source="[CreateRegion](/patterns-practices/reference/delayedregioncreationbehavior-createregion-method-mspp-regions-behaviors)">CreateRegion</a></td>
<td><div class="summary">
Method that will create the region, by calling the right <a href="/patterns-practices/reference/iregionadapter-interface-mspp-regions" data-raw-source="[IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions)">IRegionAdapter</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors" data-raw-source="[Detach](/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors)">Detach</a></td>
<td><div class="summary">
Stop monitoring the <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a> and the <a href="/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors" data-raw-source="[TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)">TargetElement</a>, so that this behavior can be garbage collected.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-onupdatingregions-method-mspp-regions-behaviors" data-raw-source="[OnUpdatingRegions](/patterns-practices/reference/delayedregioncreationbehavior-onupdatingregions-method-mspp-regions-behaviors)">OnUpdatingRegions</a></td>
<td><div class="summary">
Called when the <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a> is updating it&#39;s <a href="/patterns-practices/reference/regionmanager-regions-property-mspp-regions" data-raw-source="[Regions](/patterns-practices/reference/regionmanager-regions-property-mspp-regions)">Regions</a> collection.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-regionmanageraccessor-property-mspp-regions-behaviors" data-raw-source="[RegionManagerAccessor](/patterns-practices/reference/delayedregioncreationbehavior-regionmanageraccessor-property-mspp-regions-behaviors)">RegionManagerAccessor</a></td>
<td><div class="summary">
Sets a class that interfaces between the <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a> &#39;s static properties/events and this behavior, so this behavior can be tested in isolation.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors" data-raw-source="[TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors)">TargetElement</a></td>
<td><div class="summary">
The element that will host the Region.
</div></td>
</tr>
</tbody>
</table>

## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  