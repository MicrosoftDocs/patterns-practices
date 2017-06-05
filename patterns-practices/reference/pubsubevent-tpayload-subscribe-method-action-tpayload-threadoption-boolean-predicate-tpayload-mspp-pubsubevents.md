---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload))'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean,System.Predicate{\`0})'
ms:mtpsurl: 'pubsubevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-pubsubevents.md'
---

# PubSubEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax
```C#
public virtual SubscriptionToken Subscribe(
	Action<TPayload> action,
	ThreadOption threadOption,
	bool keepSubscriberReferenceAlive,
	Predicate<TPayload> filter
)
```

### Parameters

*action*
  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent)&gt;

The delegate that gets executed when the event is published.

*threadOption*
  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/mspp-mvvm-namespace.threadoption)

Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*
  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

When **Truetrue** (**True** in Visual Basic), the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) keeps a reference to the subscriber so it does not get garbage collected.

*filter*
  
Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[TPayload](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent)&gt;

Filter to evaluate if the subscriber should receive the event.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken)

A [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken) that uniquely identifies the added subscription.

## Remarks

 If *keepSubscriberReferenceAlive* is set to **Falsefalse** (**False** in Visual Basic), [PubSubEvent&lt;TPayload&gt;](https://review.docs.microsoft.com/en-us/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference *(keepSubscriberReferenceAlive* is **Truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior. The PubSubEvent collection is thread-safe.

## See Also
[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent)

[PubSubEvent&lt;TPayload&gt; Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent.subscribe)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)




# PubSubEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload))

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Function Subscribe ( 
	action As Action(Of TPayload),
	threadOption As ThreadOption,
	keepSubscriberReferenceAlive As Boolean,
	filter As Predicate(Of TPayload)
) As SubscriptionToken
```

### Parameters

*action* 
 
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent))

The delegate that gets executed when the event is published.

*threadOption*
  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](/patterns-practices/reference/mspp-mvvm-namespace.threadoption)

Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*
  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

When Truetrue (True in Visual Basic), the [PubSubEvent(Of TPayload)](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) keeps a reference to the subscriber so it does not get garbage collected.

*filter*  

Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [TPayload](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent))

Filter to evaluate if the subscriber should receive the event.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken)

A [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken) that uniquely identifies the added subscription.

## Remarks

 If *keepSubscriberReferenceAlive* is set to **Falsefalse** (**False** in Visual Basic), [PubSubEvent(Of TPayload)](https://review.docs.microsoft.com/en-us/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference *(keepSubscriberReferenceAlive* is **Truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior. The PubSubEvent collection is thread-safe.

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent)

[PubSubEvent(Of TPayload) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent.subscribe)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
