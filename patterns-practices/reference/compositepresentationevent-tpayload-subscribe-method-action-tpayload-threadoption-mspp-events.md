---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption)'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683953(v=PandP.50)'
---

Prism Class Library

# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption)

Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)&gt;

The delegate that gets executed when the event is raised.

*threadOption*  
Type: ThreadOption

Specifies on which thread to receive the delegate callback.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

<span id="remarksToggle"></span> The CompositePresentationEvent collection is thread-safe.

## See Also


[CompositePresentationEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent&lt;TPayload&gt; Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/gg419057(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

# CompositePresentationEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption)

Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)))

The delegate that gets executed when the event is raised.

*threadOption*  
Type: ThreadOption

Specifies on which thread to receive the delegate callback.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

<span id="remarksToggle"></span> The CompositePresentationEvent collection is thread-safe.

## See Also


[CompositePresentationEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent(Of TPayload) Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/gg419057(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))
