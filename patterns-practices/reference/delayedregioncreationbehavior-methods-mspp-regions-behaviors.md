---
TOCTitle: DelayedRegionCreationBehavior Methods
Title: 'DelayedRegionCreationBehavior Methods (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior'
ms:mtpsurl: 'delayedregioncreationbehavior-methods-mspp-regions-behaviors.md'
---


# DelayedRegionCreationBehavior Methods

The [DelayedRegionCreationBehavior](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors) type exposes the following members.

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
<td>[Attach](/patterns-practices/reference/delayedregioncreationbehavior-attach-method-mspp-regions-behaviors)</td>
<td><div class="summary">
Start monitoring the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) and the [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors) to detect when the [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors) becomes part of the Visual Tree. When that happens, the Region will be created and the behavior will [Detach](/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors).
</div></td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[CreateRegion](/patterns-practices/reference/delayedregioncreationbehavior-createregion-method-mspp-regions-behaviors)</td>
<td><div class="summary">
Method that will create the region, by calling the right [IRegionAdapter](/patterns-practices/reference/iregionadapter-interface-mspp-regions).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Detach](/patterns-practices/reference/delayedregioncreationbehavior-detach-method-mspp-regions-behaviors)</td>
<td><div class="summary">
Stop monitoring the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) and the [TargetElement](/patterns-practices/reference/delayedregioncreationbehavior-targetelement-property-mspp-regions-behaviors), so that this behavior can be garbage collected.
</div></td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[OnUpdatingRegions](/patterns-practices/reference/delayedregioncreationbehavior-onupdatingregions-method-mspp-regions-behaviors)</td>
<td><div class="summary">
Called when the [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) is updating it's [Regions](/patterns-practices/reference/regionmanager-regions-property-mspp-regions) collection.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
</tbody>
</table>

## See Also

[DelayedRegionCreationBehavior Class](/patterns-practices/reference/delayedregioncreationbehavior-class-mspp-regions-behaviors)  
[Microsoft.Practices.Prism.Regions.Behaviors Namespace](/patterns-practices/reference/mspp-regions-behaviors-namespace)  