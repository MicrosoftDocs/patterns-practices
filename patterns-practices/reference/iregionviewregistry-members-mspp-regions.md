---
TOCTitle: IRegionViewRegistry Members
Title: 'IRegionViewRegistry Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegionViewRegistry'
ms:mtpsurl: 'iregionviewregistry-members-mspp-regions.md'
---


# IRegionViewRegistry Members

The [IRegionViewRegistry](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions) type exposes the following members.

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
<td>[GetContents](/patterns-practices/reference/iregionviewregistry-getcontents-method-mspp-regions)</td>
<td><div class="summary">
Returns the contents associated with a region name.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RegisterViewWithRegion(String, Func&lt;Object&gt;)](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-string-func-object-mspp-regions)</td>
<td><div class="summary">
Registers a delegate that can be used to retrieve the content associated with a region name.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[RegisterViewWithRegion(String, Type)](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-string-type-mspp-regions)</td>
<td><div class="summary">
Registers a content type with a region name.
</div></td>
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
<td>[ContentRegistered](/patterns-practices/reference/iregionviewregistry-contentregistered-event-mspp-regions)</td>
<td><div class="summary">
Event triggered when a content is registered to a region name.
</div></td>
</tr>
</tbody>
</table>

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)