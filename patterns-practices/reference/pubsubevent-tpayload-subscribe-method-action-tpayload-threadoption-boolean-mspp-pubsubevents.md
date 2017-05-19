---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683942(v=PandP.50)'
---

Prism Class Library

PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption, Boolean)
==============================================================================================================================

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

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

    Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)<[TPayload](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))>
    The delegate that gets executed when the event is published.

*threadOption*

    Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50))
    Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

    Type: [System.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
    When **truetrue** (**True** in Visual Basic), the [PubSubEvent&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50))<br/>
A [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)) that uniquely identifies the added subscription.

## Remarks

If *keepSubscriberReferenceAlive* is set to **falsefalse** (**False** in Visual Basic), [PubSubEvent&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior.

The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50))

PubSubEvent&lt;TPayload&gt; Members

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/dn736298(v=pandp.50))

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
