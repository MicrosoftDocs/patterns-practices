---
TOCTitle: Subscribe Method
Title: 'PubSubEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md'
---

Prism Class Library

PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Subscribe Method
===============================================================

Overload List
-------------

<span id="overloadMembersTableToggle"></span>
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
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>. <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601">PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.threadoption">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d)">Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

See Also
--------


[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601)

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
