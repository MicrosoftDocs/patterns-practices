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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-contains-method-action-tpayload-mspp-pubsubevents" data-raw-source="[Contains(Action&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/pubsubevent-tpayload-contains-method-action-tpayload-mspp-pubsubevents)">Contains(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Returns <b>truetrue</b> (<b>True</b> in Visual Basic) if there is a subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8" data-raw-source="[Action&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/018hxwa8)">Action&lt;T&gt;</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/eventbase-contains-method-mspp-pubsubevents" data-raw-source="[Contains(SubscriptionToken)](/patterns-practices/reference/eventbase-contains-method-mspp-pubsubevents)">Contains(SubscriptionToken)</a></td>
<td><div class="summary">
Returns <b>truetrue</b> (<b>True</b> in Visual Basic) if there is a subscriber matching <a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents" data-raw-source="[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)">SubscriptionToken</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/eventbase-internalpublish-method-mspp-pubsubevents" data-raw-source="[InternalPublish](/patterns-practices/reference/eventbase-internalpublish-method-mspp-pubsubevents)">InternalPublish</a></td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of <a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents" data-raw-source="[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)">IEventSubscription</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="/patterns-practices/reference/eventbase-internalsubscribe-method-mspp-pubsubevents" data-raw-source="[InternalSubscribe](/patterns-practices/reference/eventbase-internalsubscribe-method-mspp-pubsubevents)">InternalSubscribe</a></td>
<td><div class="summary">
Adds the specified <a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents" data-raw-source="[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)">IEventSubscription</a> to the subscribers&#39; collection.
</div>
(Inherited from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-publish-method-mspp-pubsubevents" data-raw-source="[Publish](/patterns-practices/reference/pubsubevent-tpayload-publish-method-mspp-pubsubevents)">Publish</a></td>
<td><div class="summary">
Publishes the <a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents" data-raw-source="[PubSubEvent&amp;lt;TPayload&amp;gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)">PubSubEvent&lt;TPayload&gt;</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-mspp-pubsubevents" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-mspp-pubsubevents)">Subscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents" data-raw-source="[PublisherThread](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)">PublisherThread</a>. <a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents" data-raw-source="[PubSubEvent&amp;lt;TPayload&amp;gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)">PubSubEvent&lt;TPayload&gt;</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd" data-raw-source="[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents)">Subscribe(Action&lt;TPayload&gt;, ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd" data-raw-source="[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, Boolean)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents)">Subscribe(Action&lt;TPayload&gt;, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents" data-raw-source="[PublisherThread](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-pubsubevents" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption, Boolean)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-pubsubevents)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-pubsubevents" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption, Boolean, Predicate&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-pubsubevents)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-unsubscribe-method-action-tpayload-mspp-pubsubevents" data-raw-source="[Unsubscribe(Action&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/pubsubevent-tpayload-unsubscribe-method-action-tpayload-mspp-pubsubevents)">Unsubscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Removes the first subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8" data-raw-source="[Action&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/018hxwa8)">Action&lt;T&gt;</a> from the subscribers&#39; list.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/eventbase-unsubscribe-method-mspp-pubsubevents" data-raw-source="[Unsubscribe(SubscriptionToken)](/patterns-practices/reference/eventbase-unsubscribe-method-mspp-pubsubevents)">Unsubscribe(SubscriptionToken)</a></td>
<td><div class="summary">
Removes the subscriber matching the <a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents" data-raw-source="[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)">SubscriptionToken</a>.
</div>
(Inherited from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)