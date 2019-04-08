---
TOCTitle: EventBase Methods
Title: 'EventBase Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.EventBase'
ms:mtpsurl: 'eventbase-methods-mspp-pubsubevents.md'
---

# EventBase Methods

The [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents) type exposes the following members.

## Methods

<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
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
<td><a href="/patterns-practices/reference/eventbase-contains-method-mspp-pubsubevents" data-raw-source="[Contains](/patterns-practices/reference/eventbase-contains-method-mspp-pubsubevents)">Contains</a></td>
<td><div class="summary">
Returns <b>Truetrue</b> (<b>True</b> in Visual Basic) if there is a subscriber matching <a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents" data-raw-source="[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)">SubscriptionToken</a>.
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
<td><a href="/patterns-practices/reference/eventbase-internalpublish-method-mspp-pubsubevents" data-raw-source="[InternalPublish](/patterns-practices/reference/eventbase-internalpublish-method-mspp-pubsubevents)">InternalPublish</a></td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of <a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents" data-raw-source="[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)">IEventSubscription</a>.
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/eventbase-internalsubscribe-method-mspp-pubsubevents" data-raw-source="[InternalSubscribe](/patterns-practices/reference/eventbase-internalsubscribe-method-mspp-pubsubevents)">InternalSubscribe</a></td>
<td><div class="summary">
Adds the specified <a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents" data-raw-source="[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)">IEventSubscription</a> to the subscribers&#39; collection.
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
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/eventbase-unsubscribe-method-mspp-pubsubevents" data-raw-source="[Unsubscribe](/patterns-practices/reference/eventbase-unsubscribe-method-mspp-pubsubevents)">Unsubscribe</a></td>
<td><div class="summary">
Removes the subscriber matching the <a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents" data-raw-source="[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)">SubscriptionToken</a>.
</tr>
</tbody>
</table>

## See Also

[EventBase Class](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)  
