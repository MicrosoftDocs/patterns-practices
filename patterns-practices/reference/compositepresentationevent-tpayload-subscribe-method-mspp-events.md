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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events)">Subscribe(Action&lt;TPayload&gt;)</a></a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. <a href="/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events" data-raw-source="[CompositePresentationEvent&amp;lt;TPayload&amp;gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)">CompositePresentationEvent&lt;TPayload&gt;</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd" data-raw-source="[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events)">Subscribe(Action&lt;TPayload&gt;, ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd" data-raw-source="[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events)">Subscribe(Action&lt;TPayload&gt;, Boolean)</a></a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-events" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-events)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events" data-raw-source="[Subscribe(Action&amp;lt;TPayload&amp;gt;, ThreadOption, Boolean, Predicate&amp;lt;TPayload&amp;gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events)">Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)</a></td>
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
