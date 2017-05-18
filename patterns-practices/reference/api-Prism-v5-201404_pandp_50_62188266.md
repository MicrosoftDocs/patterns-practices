---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption, Boolean, Predicate(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption,System.Boolean,System.Predicate{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683940(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)..::.Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))
=======================================================================================================================================================================================

Subscribes a delegate to an event.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual SubscriptionToken Subscribe( Action&lt;TPayload&gt; action, ThreadOption threadOption, bool keepSubscriberReferenceAlive, Predicate&lt;TPayload&gt; filter )Public Overridable Function Subscribe ( action As Action(Of TPayload), threadOption As ThreadOption, keepSubscriberReferenceAlive As Boolean, filter As Predicate(Of TPayload) ) As SubscriptionToken
#### Parameters

action  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
The delegate that gets executed when the event is published.

<!-- -->

threadOption  
Type: ThreadOption
Specifies on which thread to receive the delegate callback.

<!-- -->

keepSubscriberReferenceAlive  
Type: [System..::.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
When trueTruetruetrue (True in Visual Basic), the [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) keeps a reference to the subscriber so it does not get garbage collected.

<!-- -->

filter  
Type: [System..::.Predicate](http://msdn2.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
Filter to evaluate if the subscriber should receive the event.

#### Return Value

Type: SubscriptionToken
A SubscriptionToken that uniquely identifies the added subscription.

Remarks
-------

<span id="remarksToggle"></span> If keepSubscriberReferenceAlive is set to falseFalsefalsefalse (False in Visual Basic), [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference (keepSubscriberReferenceAlive is trueTruetruetrue (True in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexepcted behavior. The CompositePresentationEvent collection is thread-safe.

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.events.compositepresentationevent%601.subscribe)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
