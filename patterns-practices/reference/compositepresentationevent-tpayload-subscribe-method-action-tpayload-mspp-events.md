---
TOCTitle: 'Subscribe Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0})'
ms:mtpsurl: 'compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events.md'
---

# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;)

Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied *action* delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```
public SubscriptionToken Subscribe(
	Action<TPayload> action
)
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)&gt;    
The delegate that gets executed when the event is published.

### Return Value

Type: SubscriptionToken  
A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

 The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)<br/>
[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)<br/>
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>

# CompositePresentationEvent(Of TPayload).Subscribe Method (Action(Of TPayload))

Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent(Of TPayload)](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied *action* delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```VB
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload)
) As SubscriptionToken
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events))    
The delegate that gets executed when the event is published.

### Return Value

Type: SubscriptionToken  
A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

 The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent(Of TPayload) Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)<br/>
[CompositePresentationEvent(Of TPayload) Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)<br/>
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>