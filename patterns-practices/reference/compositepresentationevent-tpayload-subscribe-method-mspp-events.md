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
<td><a href="https://msdn.microsoft.com/en-us/library/gg405768(v=pandp.50)">Subscribe(Action(Of TPayload))</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. <a href="https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)">CompositePresentationEvent(Of TPayload)</a> will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683953(v=pandp.50)">Subscribe(Action(Of TPayload), ThreadOption)</a></td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/gg405770(v=pandp.50)">	Subscribe(Action(Of TPayload), Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683959(v=pandp.50)">	Subscribe(Action(Of TPayload), ThreadOption, Boolean)</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td><a href="https://msdn.microsoft.com/en-us/library/dn683940(v=pandp.50)">	Subscribe(Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload))</a></td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
</tbody>
</table>

## See Also

[CompositePresentationEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent(Of TPayload) Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))
