---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'pubsubevent-tpayload-methods-mspp-pubsubevents.md'
---


# PubSubEvent&lt;TPayload&gt; Methods

The [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) type exposes the following members.

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
<td>[Contains(Action&lt;TPayload&gt;)](/patterns-practices/reference/pubsubevent-tpayload-contains-method-action-tpayload-mspp-pubsubevents)</td>
<td><div class="summary">
Returns <b>truetrue</b> (<b>True</b> in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Contains(SubscriptionToken)](/patterns-practices/reference/eventbase-contains-method-mspp-pubsubevents)</td>
<td><div class="summary">
Returns <b>truetrue</b> (<b>True</b> in Visual Basic) if there is a subscriber matching [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).
</div>
(Inherited from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InternalPublish](/patterns-practices/reference/eventbase-internalpublish-method-mspp-pubsubevents)</td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of [IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents).
</div>
(Inherited from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InternalSubscribe](/patterns-practices/reference/eventbase-internalsubscribe-method-mspp-pubsubevents)</td>
<td><div class="summary">
Adds the specified [IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents) to the subscribers' collection.
</div>
(Inherited from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).)</td>
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
<td>[Publish](/patterns-practices/reference/pubsubevent-tpayload-publish-method-mspp-pubsubevents)</td>
<td><div class="summary">
Publishes the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-mspp-pubsubevents)</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the [PublisherThread](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents). [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents)</td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, Boolean)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents)</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the [PublisherThread](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-pubsubevents)</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-pubsubevents)</td>
<td><div class="summary">
Subscribes a delegate to an event.
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
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Unsubscribe(Action&lt;TPayload&gt;)](/patterns-practices/reference/pubsubevent-tpayload-unsubscribe-method-action-tpayload-mspp-pubsubevents)</td>
<td><div class="summary">
Removes the first subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Unsubscribe(SubscriptionToken)](/patterns-practices/reference/eventbase-unsubscribe-method-mspp-pubsubevents)</td>
<td><div class="summary">
Removes the subscriber matching the [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).
</div>
(Inherited from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).)</td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)