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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>RegionManager</td>
<td><div class="summary">
Initializes a new instance of <a href="/patterns-practices/reference/regionmanager-class-mspp-regions" data-raw-source="[RegionManager](/patterns-practices/reference/regionmanager-class-mspp-regions)">RegionManager</a>.
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
<td><a href="/patterns-practices/reference/regionmanager-createregionmanager-method-mspp-regions" data-raw-source="[CreateRegionManager](/patterns-practices/reference/regionmanager-createregionmanager-method-mspp-regions)">CreateRegionManager</a></td>
<td><div class="summary">
Creates a new region manager.
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-getobservableregion-method-mspp-regions" data-raw-source="[GetObservableRegion](/patterns-practices/reference/regionmanager-getobservableregion-method-mspp-regions)">GetObservableRegion</a></td>
<td><div class="summary">
Returns an <a href="/patterns-practices/reference/observableobject-t-class-mspp" data-raw-source="[ObservableObject&amp;lt;T&amp;gt;](/patterns-practices/reference/observableobject-t-class-mspp)">ObservableObject&lt;T&gt;</a> wrapper that can hold an <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a>. Using this wrapper you can detect when an <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> has been created by the <a href="/patterns-practices/reference/regionadapterbase-t-class-mspp-regions" data-raw-source="[RegionAdapterBase&amp;lt;T&amp;gt;](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)">RegionAdapterBase&lt;T&gt;</a>. If the <a href="/patterns-practices/reference/observableobject-t-class-mspp" data-raw-source="[ObservableObject&amp;lt;T&amp;gt;](/patterns-practices/reference/observableobject-t-class-mspp)">ObservableObject&lt;T&gt;</a> wrapper does not yet exist, a new wrapper will be created. When the region gets created and assigned to the wrapper, you can use the <a href="/patterns-practices/reference/observableobject-t-propertychanged-event-mspp" data-raw-source="[PropertyChanged](/patterns-practices/reference/observableobject-t-propertychanged-event-mspp)">PropertyChanged</a> event to get notified of that change.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-getregioncontext-method-mspp-regions" data-raw-source="[GetRegionContext](/patterns-practices/reference/regionmanager-getregioncontext-method-mspp-regions)">GetRegionContext</a></td>
<td><div class="summary">
Gets the value of the <a href="/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions" data-raw-source="[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)">RegionContextProperty</a> attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-getregionmanager-method-mspp-regions" data-raw-source="[GetRegionManager](/patterns-practices/reference/regionmanager-getregionmanager-method-mspp-regions)">GetRegionManager</a></td>
<td><div class="summary">
Gets the value of the <a href="/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions" data-raw-source="[RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions)">RegionNameProperty</a> attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-getregionname-method-mspp-regions" data-raw-source="[GetRegionName](/patterns-practices/reference/regionmanager-getregionname-method-mspp-regions)">GetRegionName</a></td>
<td><div class="summary">
Gets the value for the <a href="/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions" data-raw-source="[RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions)">RegionNameProperty</a> attached property.
</div></td>
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-setregioncontext-method-mspp-regions" data-raw-source="[SetRegionContext](/patterns-practices/reference/regionmanager-setregioncontext-method-mspp-regions)">SetRegionContext</a></td>
<td><div class="summary">
Sets the <a href="/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions" data-raw-source="[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)">RegionContextProperty</a> attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-setregionmanager-method-mspp-regions" data-raw-source="[SetRegionManager](/patterns-practices/reference/regionmanager-setregionmanager-method-mspp-regions)">SetRegionManager</a></td>
<td><div class="summary">
Sets the <a href="/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions" data-raw-source="[RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions)">RegionManagerProperty</a> attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-setregionname-method-mspp-regions" data-raw-source="[SetRegionName](/patterns-practices/reference/regionmanager-setregionname-method-mspp-regions)">SetRegionName</a></td>
<td><div class="summary">
Sets the <a href="/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions" data-raw-source="[RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions)">RegionNameProperty</a> attached property.
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
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-updateregions-method-mspp-regions" data-raw-source="[UpdateRegions](/patterns-practices/reference/regionmanager-updateregions-method-mspp-regions)">UpdateRegions</a></td>
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
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions" data-raw-source="[AddToRegion](/patterns-practices/reference/regionmanagerextensions-addtoregion-method-mspp-regions)">AddToRegion</a></td>
<td><div class="summary">
Add a view to the Views collection of a Region. Note that the region must already exist in this regionmanager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions" data-raw-source="[RegisterViewWithRegion(String, Type)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-type-mspp-regions)">RegisterViewWithRegion(String, Type)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, by registering a type. When the region get&#39;s displayed this type will be resolved using the ServiceLocator into a concrete instance. The instance will be added to the Views collection of the region
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions" data-raw-source="[RegisterViewWithRegion(String, Func&amp;lt;Object&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-registerviewwithregion-method-iregionmanager-string-func-object-mspp-regions)">RegisterViewWithRegion(String, Func&lt;Object&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Associate a view with a region, using a delegate to resolve a concreate instance of the view. When the region get&#39;s displayed, this delelgate will be called and the result will be added to the views collection of the region.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions" data-raw-source="[RequestNavigate(String, Uri)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-mspp-regions)">RequestNavigate(String, Uri)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions" data-raw-source="[RequestNavigate(String, String)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)">RequestNavigate(String, String)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-mspp-regions)">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions" data-raw-source="[RequestNavigate(String, String, Action&amp;lt;NavigationResult&amp;gt;)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions)">RequestNavigate(String, String, Action&lt;NavigationResult&gt;)</a></td>
<td>Overloaded.
<div class="summary">
Navigates the specified region manager.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-navigationparameters-mspp-regions)">RequestNavigate(String, Uri, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, String, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-navigationparameters-mspp-regions)">RequestNavigate(String, String, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, Uri, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-uri-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(String, Uri, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target Uri, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubextension.gif" alt="Public Extension Method"/></td>
<td><a href="/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions" data-raw-source="[RequestNavigate(String, String, Action&amp;lt;NavigationResult&amp;gt;, NavigationParameters)](/patterns-practices/reference/regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-navigationparameters-mspp-regions)">RequestNavigate(String, String, Action&lt;NavigationResult&gt;, NavigationParameters)</a></td>
<td>Overloaded.
<div class="summary">
This method allows an IRegionManager to locate a specified region and navigate in it to the specified target string, passing a navigation callback and an instance of NavigationParameters, which holds a collection of object parameters.
</div>
(Defined by <a href="/patterns-practices/reference/regionmanagerextensions-class-mspp-regions" data-raw-source="[RegionManagerExtensions](/patterns-practices/reference/regionmanagerextensions-class-mspp-regions)">RegionManagerExtensions</a>.)</td>
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
<td><img src="/patterns-practices/reference/images/public-field.gif" alt="Public field"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions" data-raw-source="[RegionContextProperty](/patterns-practices/reference/regionmanager-regioncontextproperty-field-mspp-regions)">RegionContextProperty</a></td>
<td><div class="summary">
Identifies the RegionContext attached property.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-field.gif" alt="Public field"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions" data-raw-source="[RegionManagerProperty](/patterns-practices/reference/regionmanager-regionmanagerproperty-field-mspp-regions)">RegionManagerProperty</a></td>
<td><div class="summary">
Identifies the RegionManager attached property.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-field.gif" alt="Public field"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions" data-raw-source="[RegionNameProperty](/patterns-practices/reference/regionmanager-regionnameproperty-field-mspp-regions)">RegionNameProperty</a></td>
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
<td><img src="/patterns-practices/reference/images/pubproperty.gif" alt="Public property"/></td>
<td><a href="/patterns-practices/reference/regionmanager-regions-property-mspp-regions" data-raw-source="[Regions](/patterns-practices/reference/regionmanager-regions-property-mspp-regions)">Regions</a></td>
<td><div class="summary">
Gets a collection of <a href="/patterns-practices/reference/iregion-interface-mspp-regions" data-raw-source="[IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)">IRegion</a> that identify each region by name. You can use this collection to add or remove regions to the current region manager.
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
<td><img src="/patterns-practices/reference/images/pubevent.gif" alt="Public event"/><img src="/patterns-practices/reference/images/static-member.gif" alt="Static member"/></td>
<td><a href="/patterns-practices/reference/regionmanager-updatingregions-event-mspp-regions" data-raw-source="[UpdatingRegions](/patterns-practices/reference/regionmanager-updatingregions-event-mspp-regions)">UpdatingRegions</a></td>
<td><div class="summary">
Notification used by attached behaviors to update the region managers appropriatelly if needed to.
</div></td>
</tr>
</tbody>
</table>

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  