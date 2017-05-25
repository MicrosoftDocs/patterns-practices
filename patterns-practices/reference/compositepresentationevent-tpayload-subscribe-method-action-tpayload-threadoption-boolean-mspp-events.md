---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean)'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683959(v=PandP.50)'
---


# CompositePresentationEvent&lt;TPayload&gt;.Subscribe Method (Action&lt;TPayload&gt;, ThreadOption, Boolean)

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

``` C#
public SubscriptionToken Subscribe(
Action<TPayload> action,
ThreadOption threadOption,
bool keepSubscriberReferenceAlive
) 
```

### Parameters

*action*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))&gt;
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The delegate that gets executed when the event is published.

*threadOption*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: ThreadOption

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When **truetrue** (**True** in Visual Basic), the [CompositePresentationEvent&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

If keepSubscriberReferenceAlive is set to **falsefalse** (**False** in Visual Basic), [CompositePresentationEvent&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **truetrue**  (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior.

The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent&lt;TPayload&gt; Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/gg419057(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

# CompositePresentationEvent(Of TPayload).Subscribe Method (Action(Of TPayload), ThreadOption, Boolean)

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

``` VB 
'Declaration
Public Function Subscribe ( 
	action As Action(Of TPayload),
	threadOption As ThreadOption,
	keepSubscriberReferenceAlive As Boolean
) As SubscriptionToken
```

### Parameters

*action*    

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The delegate that gets executed when the event is published.

*threadOption*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: ThreadOption

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Specifies on which thread to receive the delegate callback.

*keepSubscriberReferenceAlive*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When **Truetrue** (**True** in Visual Basic), the [CompositePresentationEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: SubscriptionToken

A SubscriptionToken that uniquely identifies the added subscription.

## Remarks

If keepSubscriberReferenceAlive is set to **Falsefalse** (**False** in Visual Basic), [CompositePresentationEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50)) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied *action* delegate. If not using a WeakReference (*keepSubscriberReferenceAlive* is **Truetrue**  (**True** in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior.

The CompositePresentationEvent collection is thread-safe.

## See Also

[CompositePresentationEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent(Of TPayload) Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Subscribe Overload](https://msdn.microsoft.com/en-us/library/gg419057(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))