---
TOCTitle: 'Subscribe Method (Action(TPayload), Boolean)'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), Boolean) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405770(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)
===============================================================================================================================

Subscribes a delegate to an event that will be published on the PublisherThread.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public SubscriptionToken Subscribe( Action&lt;TPayload&gt; action, bool keepSubscriberReferenceAlive )Public Function Subscribe ( action As Action(Of TPayload), keepSubscriberReferenceAlive As Boolean ) As SubscriptionToken

### Parameters

action  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
The delegate that gets executed when the event is published.

keepSubscriberReferenceAlive  
Type: [System.Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
When trueTruetruetrue (True in Visual Basic), the [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) keeps a reference to the subscriber so it does not get garbage collected.

### Return Value

Type: SubscriptionToken
A SubscriptionToken that uniquely identifies the added subscription.

Remarks
-------

<span id="remarksToggle"></span> If keepSubscriberReferenceAlive is set to falseFalsefalsefalse (False in Visual Basic), [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference (keepSubscriberReferenceAlive is trueTruetruetrue (True in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior.

The CompositePresentationEvent collection is thread-safe.

See Also
--------


[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.events.compositepresentationevent%601.subscribe)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
