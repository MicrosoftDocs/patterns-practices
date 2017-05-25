---
TOCTitle: 'Subscribe Method (Action(TPayload))'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/dn683969(v=pandp.50)'
---

Prism Class Library

# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;)

Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)). [PubSubEvent&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action
)
```


### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))&gt;

The delegate that gets executed when the event is published.

### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50))

A [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)) that uniquely identifies the added subscription.

## Remarks

 The PubSubEvent collection is thread-safe.

## See Also


[PubSubEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))

PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/dn736298(v=pandp.50))

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

# PubSubEvent(Of TPayload).Subscribe Method (Action(Of TPayload))

Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)). [PubSubEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)))

The delegate that gets executed when the event is published.

### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50))

A [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)) that uniquely identifies the added subscription.

## Remarks

 The PubSubEvent collection is thread-safe.

## See Also


[PubSubEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))

PubSubEvent(Of TPayload) Members

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/dn736298(v=pandp.50))

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
