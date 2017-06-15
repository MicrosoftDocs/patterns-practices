---
TOCTitle: Subscribe Method
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe'
ms:mtpsurl: 'compositepresentationevent-tpayload-subscribe-method-mspp-events.md'
---


# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method

## Overload List

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
<td>[Subscribe(Action&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  
