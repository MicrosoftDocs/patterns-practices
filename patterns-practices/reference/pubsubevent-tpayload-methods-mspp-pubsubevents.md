---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'pubsubevent-tpayload-methods-mspp-pubsubevents.md'
---


# PubSubEvent(Of TPayload) Methods

The [PubSubEvent(Of TPayload)](pubsubevent-tpayload-class-mspp-pubsubevents.md) type exposes the following members.

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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.contains(system.action%7b%600%7d)">Contains(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;T&gt;</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Contains(SubscriptionToken)</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase.internalpublish(system.object%5b%5d)">InternalPublish</a></td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription)">InternalSubscribe</a></td>
<td><div class="summary">
Adds the specified <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a> to the subscribers' collection.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683930(v=pandp.50)">Publish</a></td>
<td><div class="summary">
Publishes the <a href="https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)">PubSubEvent&lt;TPayload&gt;</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683969(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>. <a href="https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)">PubSubEvent&lt;TPayload&gt;</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736155(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683949(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683942(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736225(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736235(v=pandp.50)">Unsubscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Removes the first subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;T&gt;</a> from the subscribers' list.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Unsubscribe(SubscriptionToken)</a></td>
<td><div class="summary">
Removes the subscriber matching the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](pubsubevent-tpayload-class-mspp-pubsubevents.md)

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)