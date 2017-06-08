---
TOCTitle: 'CompositePresentationEvent(TPayload) Methods'
Title: 'CompositePresentationEvent(TPayload) Methods (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1'
ms:mtpsurl: 'compositepresentationevent-tpayload-methods-mspp-events.md'
---


# CompositePresentationEvent&lt;TPayload&gt; Methods

The [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) type exposes the following members.

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
<td>Contains(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-contains-method-action-tpayload-mspp-events">Contains(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Returns <strong>truetrue</strong> (<strong>True</strong> in Visual Basic) if there is a subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;T&gt;</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
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
<td>InternalPublish</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>InternalSubscribe</td>
<td>(Inherited from EventBase.)</td>
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
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-publish-method-mspp-events">Publish</a></td>
<td><div class="summary">
Publishes the <a href="/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events">CompositePresentationEvent&lt;TPayload&gt;</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events">Subscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. <a href="/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events">CompositePresentationEvent&lt;TPayload&gt;</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events">Subscribe(Action&lt;TPayload&gt;, ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events">Subscribe(Action&lt;TPayload&gt;, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-events">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>Unsubscribe(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-unsubscribe-method-action-tpayload-mspp-events">Unsubscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Removes the first subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;T&gt;</a> from the subscribers' list.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)

[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)
