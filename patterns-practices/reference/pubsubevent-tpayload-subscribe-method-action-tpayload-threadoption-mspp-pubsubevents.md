---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption)'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-pubsubevents.md'
---

# PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)

Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public SubscriptionToken Subscribe( Action&lt;TPayload&gt; action, ThreadOption threadOption )Public Function Subscribe ( action As Action(Of TPayload), threadOption As ThreadOption ) As SubscriptionToken

### Parameters

action  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent%601)&gt;)&gt;)
The delegate that gets executed when the event is raised.

threadOption  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/mspp-mvvm-namespace.threadoption)
Specifies on which thread to receive the delegate callback.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken)
A [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken) that uniquely identifies the added subscription.

## Remarks

 The PubSubEvent collection is thread-safe.

## See Also
[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent%601)

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
