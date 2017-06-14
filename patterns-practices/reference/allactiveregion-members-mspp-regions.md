---
TOCTitle: AllActiveRegion Members
Title: 'AllActiveRegion Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.AllActiveRegion'
ms:mtpsurl: 'allactiveregion-members-mspp-regions.md'
---

# AllActiveRegion Members

The [AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions) type exposes the following members.

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
<td>AllActiveRegion</td>
<td><div class="summary">
Initializes a new instance of the [AllActiveRegion](/patterns-practices/reference/allactiveregion-class-mspp-regions) class
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
<td>[Activate](/patterns-practices/reference/region-activate-method-mspp-regions)</td>
<td><div class="summary">
Marks the specified view as active.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object)](/patterns-practices/reference/region-add-method-object-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String)](/patterns-practices/reference/region-add-method-object-string-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Add(Object, String, Boolean)](/patterns-practices/reference/region-add-method-object-string-boolean-mspp-regions)</td>
<td><div class="summary">
Adds a new view to the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Deactivate](/patterns-practices/reference/allactiveregion-deactivate-method-mspp-regions)</td>
<td><div class="summary">
Deactive is not valid in this Region. This method will always throw [InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a).
</div>
(Overrides [Region.Deactivate(Object)](/patterns-practices/reference/region-deactivate-method-mspp-regions).)</td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetView](/patterns-practices/reference/region-getview-method-mspp-regions)</td>
<td><div class="summary">
Returns the view instance that was added to the region using a specific name.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Remove](/patterns-practices/reference/region-remove-method-mspp-regions)</td>
<td><div class="summary">
Removes the specified view from the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/region-requestnavigate-method-uri-action-navigationresult-mspp-regions)</td>
<td><div class="summary">
Initiates navigation to the specified target.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters) ](/patterns-practices/reference/region-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions)</td>
<td><div class="summary">
Initiates navigation to the specified target.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
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
<td>[ActiveViews](/patterns-practices/reference/allactiveregion-activeviews-property-mspp-regions)</td>
<td><div class="summary">
Gets a readonly view of the collection of all the active views in the region. These are all the added views.
</div>
(Overrides [Region.ActiveViews](/patterns-practices/reference/region-activeviews-property-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Behaviors](/patterns-practices/reference/region-behaviors-property-mspp-regions)</td>
<td><div class="summary">
Gets the collection of [IRegionBehavior](/patterns-practices/reference/iregionbehavior-interface-mspp-regions)s that can extend the behavior of regions.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Context](/patterns-practices/reference/region-context-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets a context for the region. This value can be used by the user to share context with the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Protected property](/patterns-practices/reference/images/protproperty.gif)</td>
<td>[ItemMetadataCollection](/patterns-practices/reference/region-itemmetadatacollection-property-mspp-regions)</td>
<td><div class="summary">
Gets the collection with all the views along with their metadata.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Name](/patterns-practices/reference/region-name-property-mspp-regions)</td>
<td><div class="summary">
Gets the name of the region that uniequely identifies the region within a [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[NavigationService](/patterns-practices/reference/region-navigationservice-property-mspp-regions)</td>
<td><div class="summary">
Gets the navigation service.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[RegionManager](/patterns-practices/reference/region-regionmanager-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the [IRegionManager](/patterns-practices/reference/iregionmanager-interface-mspp-regions) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as **Truetrue** (**True** in Visual Basic).
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[SortComparison](/patterns-practices/reference/region-sortcomparison-property-mspp-regions)</td>
<td><div class="summary">
Gets or sets the comparison used to sort the views.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Views](/patterns-practices/reference/region-views-property-mspp-regions)</td>
<td><div class="summary">
Gets a readonly view of the collection of views in the region.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
</tbody>
</table>

## Events

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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)</td>
<td>[PropertyChanged](/patterns-practices/reference/region-propertychanged-event-mspp-regions)</td>
<td><div class="summary">
Occurs when a property value changes.
</div>
(Inherited from [Region](/patterns-practices/reference/region-class-mspp-regions).)</td>
</tr>
</tbody>
</table>

## See Also

[AllActiveRegion Class](/patterns-practices/reference/allactiveregion-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  