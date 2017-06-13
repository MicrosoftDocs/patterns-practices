---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption)'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents.md'
---

# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption)

Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action,
	ThreadOption threadOption
)
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)&gt;

The delegate that gets executed when the event is raised.

*threadOption*  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)

Specifies on which thread to receive the delegate callback.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)

A [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that uniquely identifies the added subscription.

## Remarks

The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>

# PubSubEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption)

Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload),
	threadOption As ThreadOption
) As SubscriptionToken
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents))

The delegate that gets executed when the event is raised.

*threadOption*  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)

Specifies on which thread to receive the delegate callback.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)

A [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that uniquely identifies the added subscription.

## Remarks

The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
PubSubEvent(Of TPayload) Members

[Subscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>