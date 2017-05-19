---
TOCTitle: 'Subscribe Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405768(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;))
======================================================================================================================

Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public SubscriptionToken Subscribe( Action&lt;TPayload&gt; action )Public Function Subscribe ( action As Action(Of TPayload) ) As SubscriptionToken
#### Parameters

action  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
The delegate that gets executed when the event is published.

#### Return Value

Type: SubscriptionToken
A SubscriptionToken that uniquely identifies the added subscription.

Remarks
-------

<span id="remarksToggle"></span> The CompositePresentationEvent collection is thread-safe.

See Also
--------


[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.events.compositepresentationevent%601.subscribe)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
