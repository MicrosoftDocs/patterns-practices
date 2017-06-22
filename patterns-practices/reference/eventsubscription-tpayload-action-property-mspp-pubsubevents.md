---
TOCTitle: Action Property
Title: 'EventSubscription(TPayload).Action Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Action'
ms:mtpsurl: 'eventsubscription-tpayload-action-property-mspp-pubsubevents.md'
---


# EventSubscription&lt;TPayload&gt;.Action Property

Gets the target [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) that is referenced by the [IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public Action<TPayload> Action { get; }
```

### Property Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)&gt;  
An [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) or nullNothingnullptra null reference (Nothing in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)  
EventSubscription&lt;TPayload&gt; Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  


# EventSubscription(Of TPayload).Action Property

Gets the target [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) that is referenced by the [IDelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public ReadOnly Property Action As Action(Of TPayload)
	Get
```

### Property Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents))  
An [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) or **Nothing**a null reference (**Nothing** in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription(Of TPayload) Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)  
EventSubscription(Of TPayload) Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)