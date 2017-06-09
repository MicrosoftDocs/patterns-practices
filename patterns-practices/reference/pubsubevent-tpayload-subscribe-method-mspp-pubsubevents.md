---
TOCTitle: Subscribe Method
Title: 'PubSubEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md'
---

# PubSubEvent(Of TPayload).Subscribe Method

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
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-mspp-pubsubevents
">Subscribe(Action(Of TPayload)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents
">PublisherThread</a>. <a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents">PubSubEvent(Of TPayload)</a> will maintain a <a href="http://msdn2.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied <em>action</em> delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents
">Subscribe(Action(Of TPayload), ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a <a href="http://msdn2.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied <em>action</em> delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents
">Subscribe(Action(Of TPayload), Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the <a href="https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)">PublisherThread</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-pubsubevents">Subscribe(Action(Of TPayload), ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/images/public-method.gif)</td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-pubsubevents
">Subscribe(Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)  
PubSubEvent(Of TPayload) Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)
