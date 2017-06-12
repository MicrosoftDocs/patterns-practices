---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean)'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-pubsubevents.md'
---
## PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption, Boolean)
Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action,
	ThreadOption threadOption,
	bool keepSubscriberReferenceAlive
)
```

```VB
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload),
	threadOption As ThreadOption,
	keepSubscriberReferenceAlive As Boolean
) As SubscriptionToken
```
### Parameters

*action*

    Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)<[TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)>
    The delegate that gets executed when the event is published.

*threadOption*

    Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)
    Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

    Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
    When **truetrue** (**True** in Visual Basic), the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)<br/>
A [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that uniquely identifies the added subscription.

## Remarks

If *keepSubscriberReferenceAlive* is set to **falsefalse** (**False** in Visual Basic), [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior.

The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](/patterns-practices/reference/pubsubevent-tpayload-subscribe-method-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>