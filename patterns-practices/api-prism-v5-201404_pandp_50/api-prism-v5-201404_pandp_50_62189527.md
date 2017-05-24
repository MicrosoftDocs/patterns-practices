---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736289(v=PandP.50)'
---

Prism Class Library

DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)..::.InvokeAction Method
==================================================================================

Invokes the specified [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public override void InvokeAction( Action&lt;TPayload&gt; action, TPayload argument )Public Overrides Sub InvokeAction ( action As Action(Of TPayload), argument As TPayload )
#### Parameters

action  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)&gt;)&gt;)
The action to execute.

<!-- -->

argument  
Type: [TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)
The payload to pass action while invoking it.

See Also
--------

<span id="seeAlsoToggle"></span>
[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
