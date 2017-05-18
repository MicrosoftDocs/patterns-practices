---
TOCTitle: 'Subscribe Method (Action(TPayload), Boolean)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), Boolean) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},System.Boolean)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683949(v=PandP.50)'
---

Prism Class Library

PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)..::.Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)
================================================================================================================

Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public SubscriptionToken Subscribe( Action&lt;TPayload&gt; action, bool keepSubscriberReferenceAlive )Public Function Subscribe ( action As Action(Of TPayload), keepSubscriberReferenceAlive As Boolean ) As SubscriptionToken
#### Parameters

action  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601)&gt;)&gt;)
The delegate that gets executed when the event is published.

<!-- -->

keepSubscriberReferenceAlive  
Type: [System..::.Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
When trueTruetruetrue (True in Visual Basic), the [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601) keeps a reference to the subscriber so it does not get garbage collected.

#### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken)
A [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken) that uniquely identifies the added subscription.

Remarks
-------

<span id="remarksToggle"></span> If keepSubscriberReferenceAlive is set to falseFalsefalsefalse (False in Visual Basic), [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate. If not using a WeakReference (keepSubscriberReferenceAlive is trueTruetruetrue (True in Visual Basic)), the user must explicitly call Unsubscribe for the event when disposing the subscriber in order to avoid memory leaks or unexpected behavior.

The PubSubEvent collection is thread-safe.

See Also
--------

<span id="seeAlsoToggle"></span>
[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
