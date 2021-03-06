---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean,System.Predicate{\`0})'
ms:mtpsurl: 'compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events.md'
---

# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

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
      
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)&gt;<br/>
The delegate that gets executed when the event is published.

*threadOption*

Type: ThreadOption<br/>
Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)<br/>
When **truetrue** (**True** in Visual Basic), the [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) keeps a reference to the subscriber so it does not get garbage collected.

*filter*

Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)<[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)><br/>
Filter to evaluate if the subscriber should receive the event.

### Return Value

Type: SubscriptionToken<br/>
A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

If *keepSubscriberReferenceAlive* is set to **falsefalse** (**False** in Visual Basic), [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior. The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  

# CompositePresentationEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload))

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

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
      
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events))<br/>
The delegate that gets executed when the event is published.

*threadOption*

Type: ThreadOption<br/>
Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)<br/>
When trueTruetruetrue (True in Visual Basic), the [CompositePresentationEvent(Of TPayload)](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) keeps a reference to the subscriber so it does not get garbage collected.

*filter*

Type: [System.Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events))<br/>
Filter to evaluate if the subscriber should receive the event.

### Return Value

Type: SubscriptionToken<br/>
A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

If *keepSubscriberReferenceAlive* is set to **Falsefalse** (**False** in Visual Basic), [CompositePresentationEvent(Of TPayload)](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **Truetrue** (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior. The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent(Of TPayload) Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent(Of TPayload) Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)