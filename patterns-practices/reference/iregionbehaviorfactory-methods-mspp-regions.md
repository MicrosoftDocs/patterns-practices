---
TOCTitle: IRegionBehaviorFactory Methods
Title: 'IRegionBehaviorFactory Methods (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Regions.IRegionBehaviorFactory'
ms:mtpsurl: 'iregionbehaviorfactory-methods-mspp-regions.md'
---


# IRegionBehaviorFactory Methods

The [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions) type exposes the following members.

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
<td>[AddIfMissing](/patterns-practices/reference/iregionbehaviorfactory-addifmissing-method-mspp-regions)</td>
<td><div class="summary">
Adds a particular type of RegionBehavior if it was not already registered. the behaviorKey string is used to check if the behavior is already present
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ContainsKey](/patterns-practices/reference/iregionbehaviorfactory-containskey-method-mspp-regions)</td>
<td><div class="summary">
Determines whether a behavior with the specified key already exists
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CreateFromKey](/patterns-practices/reference/iregionbehaviorfactory-createfromkey-method-mspp-regions)</td>
<td><div class="summary">
Creates an instance of the Behaviortype that's registered using the specified key.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetEnumerator](http://msdn.microsoft.com/en-us/library/s793z9y2)</td>
<td><div class="summary">
Returns an enumerator that iterates through the collection.
</div>
(Inherited from [IEnumerable](http://msdn.microsoft.com/en-us/library/9eekhta0)(Of [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetEnumerator](http://msdn.microsoft.com/en-us/library/5zae5365)</td>
<td><div class="summary">
Returns an enumerator that iterates through a collection.
</div>
(Inherited from [IEnumerable](http://msdn.microsoft.com/en-us/library/h1x9x1b1).)</td>
</tr>
</tbody>
</table>

## See Also

[IRegionBehaviorFactory Interface](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>