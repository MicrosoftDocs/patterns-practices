---
TOCTitle: 'Subscribe Method (Action(TPayload), Boolean)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), Boolean) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},System.Boolean)'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-pubsubevents.md'
---


# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, Boolean)

Subscribes a delegate to an event that will be published on the [PublisherThread](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)&gt;

The delegate that gets executed when the event is published.

*keepSubscriberReferenceAlive*  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

When **truetrue** (**True** in Visual Basic), the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)

A [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that uniquely identifies the added subscription.

## Remarks

 If *keepSubscriberReferenceAlive* is set to **falsefalse** (**False** in Visual Basic), [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior.

The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)

PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-mspp-pubsubevents)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)