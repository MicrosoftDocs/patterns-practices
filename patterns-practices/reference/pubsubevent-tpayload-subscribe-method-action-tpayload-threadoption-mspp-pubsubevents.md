---
TOCTitle: 'Subscribe Method (Action(TPayload), ThreadOption)'
Title: 'PubSubEvent(TPayload).Subscribe Method (Action(TPayload), ThreadOption) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Subscribe(System.Action{\`0},Microsoft.Practices.Prism.PubSubEvents.ThreadOption)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736155(v=PandP.50)'
---

Prism Class Library

PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Subscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)
=====================================================================================================================

Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public SubscriptionToken Subscribe( Action&lt;TPayload&gt; action, ThreadOption threadOption )Public Function Subscribe ( action As Action(Of TPayload), threadOption As ThreadOption ) As SubscriptionToken
#### Parameters

action  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601)&gt;)&gt;)
The delegate that gets executed when the event is raised.

threadOption  
Type: [Microsoft.Practices.Prism.PubSubEvents.ThreadOption](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption)
Specifies on which thread to receive the delegate callback.

#### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken)
A [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken) that uniquely identifies the added subscription.

Remarks
-------

<span id="remarksToggle"></span> The PubSubEvent collection is thread-safe.

See Also
--------

<span id="seeAlsoToggle"></span>
[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Subscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
