---
TOCTitle: Subscribe Method
Title: 'PubSubEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md'
---

# PubSubEvent&lt;TPayload&gt;.Subscribe Method

## Overload List

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683969(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)">PublisherThread</a>. <a href="https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)">PubSubEvent&lt;TPayload&gt;</a> will maintain a <a href="http://msdn2.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied <em>action</em> delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736155(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn2.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied <em>action</em> delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683949(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683942(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn736225(v=pandp.50)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))  
PubSubEvent&lt;TPayload&gt; Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
