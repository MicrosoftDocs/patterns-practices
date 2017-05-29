---
TOCTitle: 'Subscribe Method (Action(TPayload), Boolean)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), Boolean) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},System.Boolean)'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents.md'
---

# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, Boolean)

Subscribes a delegate to an event that will be published on the [PublisherThread](threadoption-enumeration-mspp-pubsubevents.md).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
## Syntax
```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action,
	bool keepSubscriberReferenceAlive
)
```
```VB
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload),
	keepSubscriberReferenceAlive As Boolean
) As SubscriptionToken
```
### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](pubsubevent-tpayload-class-mspp-pubsubevents.md)&gt;

The delegate that gets executed when the event is published.

*keepSubscriberReferenceAlive*  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

When **truetrue** (**True** in Visual Basic), the [PubSubEvent&lt;TPayload&gt;](pubsubevent-tpayload-class-mspp-pubsubevents.md) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md)

A [SubscriptionToken](subscriptiontoken-class-mspp-pubsubevents.md) that uniquely identifies the added subscription.

## Remarks

 If *keepSubscriberReferenceAlive* is set to **falsefalse** (**False** in Visual Basic), [PubSubEvent&lt;TPayload&gt;](pubsubevent-tpayload-class-mspp-pubsubevents.md) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior.

The PubSubEvent collection is thread-safe.

## See Also
[PubSubEvent&lt;TPayload&gt; Class](pubsubevent-tpayload-class-mspp-pubsubevents.md)

PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](pubsubevent-tpayload-subscribe-method-mspp-pubsubevents.md)

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)
