---
TOCTitle: Subscribe Method
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe'
ms:mtpsurl: 'compositepresentationevent-tpayload-subscribe-method-mspp-events.md'
---


# CompositePresentationEvent(Of TPayload).Subscribe Method

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
<td>[Subscribe(Action(Of TPayload))](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent(Of TPayload)](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action(Of TPayload), ThreadOption)](https://msdn.microsoft.com/en-us/library/dn683953(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action(Of TPayload), Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action(Of TPayload), ThreadOption, Boolean)](https://msdn.microsoft.com/en-us/library/dn683959(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload))](https://msdn.microsoft.com/en-us/library/dn683940(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositePresentationEvent(Of TPayload) Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)<br/> 
[CompositePresentationEvent(Of TPayload) Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>
