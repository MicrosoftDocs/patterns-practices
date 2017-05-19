---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683938(v=PandP.50)'
---

Prism Class Library

# PubSubEvent(Of TPayload) Methods

The [PubSubEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) type exposes the following members.

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
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.contains(system.action%7b%600%7d)">Contains(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Contains(SubscriptionToken)</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
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
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalpublish(system.object%5b%5d)">InternalPublish</a></td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription)">InternalSubscribe</a></td>
<td><div class="summary">
Adds the specified <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a> to the subscribers' collection.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
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
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.publish(%600)">Publish</a></td>
<td><div class="summary">
Publishes the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601">PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>. <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601">PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.unsubscribe(system.action%7b%600%7d)">Unsubscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Removes the first subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a> from the subscribers' list.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Unsubscribe(SubscriptionToken)</a></td>
<td><div class="summary">
Removes the subscriber matching the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div>
(Inherited from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.)</td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)  )

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
