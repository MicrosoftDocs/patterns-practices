---
TOCTitle: 'Unsubscribe Method (Action(TPayload))'
Title: 'PubSubEvent(TPayload).Unsubscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Unsubscribe(System.Action{\`0})'
ms:mtpsurl: 'pubsubevent-tpayload-unsubscribe-method-action-tpayload-mspp-pubsubevents.md'
---


# PubSubEvent&lt;TPayload&gt;.Unsubscribe Method (Action&lt;TPayload&gt;)

Removes the first subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void Unsubscribe(
	Action<TPayload> subscriber
)
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)&gt;

The [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

## See Also

[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
PubSubEvent&lt;TPayload&gt; Members

[Unsubscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-unsubscribe-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>

# PubSubEvent(Of TPayload).Unsubscribe Method (Action(Of TPayload))

Removes the first subscriber matching [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Sub Unsubscribe ( 
	subscriber As Action(Of TPayload)
)
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents))

The [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
PubSubEvent(Of TPayload) Members

[Unsubscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-unsubscribe-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>