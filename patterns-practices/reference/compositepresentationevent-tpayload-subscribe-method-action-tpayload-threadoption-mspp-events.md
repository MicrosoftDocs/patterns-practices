---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption)'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption)'
ms:mtpsurl: 'compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events.md'
---


# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption)

Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public SubscriptionToken Subscribe(
	Action<TPayload> action,
	ThreadOption threadOption
)
```


### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events.md&gt;

The delegate that gets executed when the event is raised.

*threadOption*  
Type: ThreadOption

Specifies on which thread to receive the delegate callback.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

 The CompositePresentationEvent collection is thread-safe.

## See Also


[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  

# CompositePresentationEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption)

Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events))

The delegate that gets executed when the event is raised.

*threadOption*  
Type: ThreadOption

Specifies on which thread to receive the delegate callback.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

 The CompositePresentationEvent collection is thread-safe.

## See Also


[CompositePresentationEvent(Of TPayload) Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent(Of TPayload) Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Subscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)