---
TOCTitle: 'Subscribe Method (Action(TPayload))'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0})'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-mspp-pubsubevents.md'
---

Prism Class Library

# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;)

Subscribes a delegate to an event that will be published on the [PublisherThread](threadoption-enumeration-mspp-pubsubevents.md). [PubSubEvent&lt;TPayload&gt;](pubsubevent-tpayload-class-mspp-pubsubevents.md) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action
)
```


### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](pubsubevent-tpayload-class-mspp-pubsubevents.md)&gt;

The delegate that gets executed when the event is published.

### Return Value

Type: [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md)

A [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md) that uniquely identifies the added subscription.

## Remarks

 The PubSubEvent collection is thread-safe.

## See Also


[PubSubEvent&lt;TPayload&gt; Class](pubsubevent-tpayload-class-mspp-pubsubevents.md)

PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md)

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)

# PubSubEvent(Of TPayload).Subscribe Method (Action(Of TPayload))

Subscribes a delegate to an event that will be published on the [PublisherThread](threadoption-enumeration-mspp-pubsubevents.md). [PubSubEvent(Of TPayload)](pubsubevent-tpayload-class-mspp-pubsubevents.md) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload)
) As SubscriptionToken
```


### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](pubsubevent-tpayload-class-mspp-pubsubevents.md))

The delegate that gets executed when the event is published.

### Return Value

Type: [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md)

A [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md) that uniquely identifies the added subscription.

## Remarks

 The PubSubEvent collection is thread-safe.

## See Also


[PubSubEvent(Of TPayload) Class](pubsubevent-tpayload-class-mspp-pubsubevents.md)

PubSubEvent(Of TPayload) Members

[Subscribe Overload](pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md)

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)
