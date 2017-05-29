---
TOCTitle: Action Property
Title: 'EventSubscription(TPayload).Action Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Action'
ms:mtpsurl: 'eventsubscription-tpayload-action-property-mspp-pubsubevents.md'
---

# EventSubscription&lt;TPayload&gt;.Action Property

Gets the target [Action &lt;T &gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) that is referenced by the [IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public Action<TPayload> Action { get; }
```

#### Property Value

Type: [Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))&gt;

An [Action &lt;T &gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) or **null**a null reference (**Nothing** in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription &lt;TPayload &gt; Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription &lt;TPayload &gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))


# EventSubscription(Of TPayload).Action Property

Gets the target [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) that is referenced by the [IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public ReadOnly Property Action As Action(Of TPayload)
	Get
```

#### Property Value

Type: [Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50)))

An [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) or **Nothing**a null reference (**Nothing** in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
