---
TOCTitle: Action Property
Title: 'EventSubscription(TPayload).Action Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Action'
ms:mtpsurl: 'eventsubscription-tpayload-action-property-mspp-pubsubevents.md'
---


# EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).Action Property

Gets the target [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) that is referenced by the [IDelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public Action&lt;TPayload&gt; Action { get; }Public ReadOnly Property Action As Action(Of TPayload) Get
### Property Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601)&gt;)&gt;)
An [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) or nullNothingnullptra null reference (Nothing in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601)

[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)