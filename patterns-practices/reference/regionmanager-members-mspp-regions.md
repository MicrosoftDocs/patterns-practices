---
TOCTitle: RegionManager Members
Title: 'RegionManager Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.RegionManager'
ms:mtpsurl: 'regionmanager-members-mspp-regions.md'
---


# RegionManager Members

The [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions) type exposes the following members.

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
<td>RegionManager</td>
<td><div class="summary">
Initializes a new instance of [RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions).
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
<td>[CreateRegionManager](/patterns-practices/reference/regionmanager-createregionmanager-method-mspp-regions)</td>
<td><div class="summary">
Creates a new region manager.
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetObservableRegion](/patterns-practices/reference/regionmanager-getobservableregion-method-mspp-regions)</td>
<td><div class="summary">
Returns an [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper that can hold an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions). Using this wrapper you can detect when an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) has been created by the [RegionAdapterBase&lt;T&gt;](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions). If the [ObservableObject&lt;T&gt;](/patterns-practices/reference/observableobject-t-class-mspp) wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the [PropertyChanged](/patterns-practices/reference/observableobject-t-propertychanged-event-mspp) event to get notified of that change.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetRegionContext](/patterns-practices/reference/regionmanager-getregioncontext-method-mspp-regions)</td>
<td><div class="summary">
Gets the value of the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) attached property.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetRegionManager](/patterns-practices/reference/regionmanager-getregionmanager-method-mspp-regions)</td>
<td><div class="summary">
Gets the value of the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[GetRegionName](/patterns-practices/reference/regionmanager-getregionname-method-mspp-regions)</td>
<td><div class="summary">
Gets the value for the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property.
</div></td>
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SetRegionContext](/patterns-practices/reference/regionmanager-setregioncontext-method-mspp-regions)</td>
<td><div class="summary">
Sets the [RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions) attached property.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SetRegionManager](/patterns-practices/reference/regionmanager-setregionmanager-method-mspp-regions)</td>
<td><div class="summary">
Sets the [RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions) attached property.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[SetRegionName](/patterns-practices/reference/regionmanager-setregionname-method-mspp-regions)</td>
<td><div class="summary">
Sets the [RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions) attached property.
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
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[UpdateRegions](/patterns-practices/reference/regionmanager-updateregions-method-mspp-regions)</td>
<td><div class="summary">
Notifies attached behaviors to update the region managers appropriatelly if needed to.
</div></td>
</tr>
</tbody>
</table>

## Extension Methods


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
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[AddToRegion](/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions)</td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RegisterViewWithRegion(String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get's displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RegisterViewWithRegion(String, Func&lt;Object&gt;)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get's displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="even">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
</tr>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[RequestNavigate(String, String, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions)</td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by [RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions).)</td>
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
<td>[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)</td>
<td><div class="summary">
Identifies the RegionContext attached property.
</div></td>
</tr>
<tr class="even">
<td>![Public field](/patterns-practices/reference/images/public-field.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions)</td>
<td><div class="summary">
Identifies the RegionManager attached property.
</div></td>
</tr>
<tr class="odd">
<td>![Public field](/patterns-practices/reference/images/public-field.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions)</td>
<td><div class="summary">
Identifies the RegionName attached property.
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
<td>[Regions](/patterns-practices/reference/regionmanager-regions-property-mspp-regions)</td>
<td><div class="summary">
Gets a collection of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that identify each region by name. You can use this collection to add or remove regions to the current region manager.
</div></td>
</tr>
</tbody>
</table>

## Attached Properties


|                                                                                                           | Name                                                                                                        | Description |
|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|-------------|
| ![Public attached property](/patterns-practices/reference/images/pubproperty.gif) | [RegionContext](/patterns-practices/reference/regionmanager-regioncontext-attached-property-mspp-regions) |             |
| ![Public attached property](/patterns-practices/reference/images/pubproperty.gif) | [RegionManager](/patterns-practices/reference/regionmanager-regionmanager-attached-property-mspp-regions) |             |
| ![Public attached property](/patterns-practices/reference/images/pubproperty.gif) | [RegionName](/patterns-practices/reference/regionmanager-regionname-attached-property-mspp-regions)       |             |

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
<td>![Public event](/patterns-practices/reference/images/pubevent.gif)![Static member](/patterns-practices/reference/images/static-member.gif)</td>
<td>[UpdatingRegions](/patterns-practices/reference/regionmanager-updatingregions-event-mspp-regions)</td>
<td><div class="summary">
Notification used by attached behaviors to update the region managers appropriatelly if needed to.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>