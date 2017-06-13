---
TOCTitle: MefRegionViewRegistry Members
Title: 'MefRegionViewRegistry Members (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Regions.MefRegionViewRegistry'
ms:mtpsurl: 'mefregionviewregistry-members-mspp-mefextensions-regions.md'
---


# MefRegionViewRegistry Members

The [MefRegionViewRegistry](/patterns-practices/reference/mefregionviewregistry-class-mspp-mefextensions-regions) type exposes the following members.

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
<td>MefRegionViewRegistry</td>
<td><div class="summary">
Initializes a new instance of the <a href="/patterns-practices/reference/mefregionviewregistry-class-mspp-mefextensions-regions">MefRegionViewRegistry</a> class.
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
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="/patterns-practices/reference/regionviewregistry-createinstance-method-mspp-regions">CreateInstance</a></td>
<td><div class="summary">
Creates an instance of a registered view <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions">RegionViewRegistry</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/regionviewregistry-getcontents-method-mspp-regions">GetContents</a></td>
<td><div class="summary">
Returns the contents registered for a region.
</div>
(Inherited from <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions">RegionViewRegistry</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/regionviewregistry-registerviewwithregion-method-string-func-object-mspp-regions">RegisterViewWithRegion(String, Func(Of Object))</a></td>
<td><div class="summary">
Registers a delegate that can be used to retrieve the content associated with a region name.
</div>
(Inherited from <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions">RegionViewRegistry</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/regionviewregistry-registerviewwithregion-method-string-type-mspp-regions">RegisterViewWithRegion(String, Type)</a></td>
<td><div class="summary">
Registers a content type with a region name.
</div>
(Inherited from <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions">RegionViewRegistry</a>.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
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
<td><a href="/patterns-practices/reference/regionviewregistry-contentregistered-event-mspp-regions">ContentRegistered</a></td>
<td><div class="summary">
Occurs whenever a new view is registered.
</div>
(Inherited from <a href="/patterns-practices/reference/regionviewregistry-class-mspp-regions">RegionViewRegistry</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[MefRegionViewRegistry Class](/patterns-practices/reference/mefregionviewregistry-class-mspp-mefextensions-regions)<br/>
[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](/patterns-practices/reference/mspp-mefextensions-regions-namespace)<br/>