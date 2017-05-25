---
TOCTitle: 'CompositePresentationEvent(TPayload) Methods'
Title: 'CompositePresentationEvent(TPayload) Methods (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1'
ms:mtpsurl: 'compositepresentationevent-tpayload-methods-mspp-events.md'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Methods
=================================================================

The [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
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
<td>Contains(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.contains(system.action%7b%600%7d)">Contains(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a>.
</div></td>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
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
<td><img src="https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td>InternalPublish</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td>InternalSubscribe</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.publish(%600)">Publish</a></td>
<td><div class="summary">
Publishes the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601">CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601">CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
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
<td>Unsubscribe(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.unsubscribe(system.action%7b%600%7d)">Unsubscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Removes the first subscriber matching <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a> from the subscribers' list.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
