---
TOCTitle: 'EventSubscription(TPayload) Class'
Title: 'EventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683956(v=PandP.50)'
---

Prism Class Library

EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class
======================================================

Provides a way to retrieve a [Delegate](http://msdn2.microsoft.com/en-us/library/y22acf51) to execute an action depending on the value of a second filter predicate that returns true if the action should execute.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public class EventSubscription&lt;TPayload&gt; : IEventSubscription Public Class EventSubscription(Of TPayload) Implements IEventSubscription
Type Parameters
---------------

<span id="templatesToggle"></span>
TPayload  
The type to use for the generic [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz) types.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.PubSubEvents..::.EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)
    [Microsoft.Practices.Prism.PubSubEvents..::.BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)
    [Microsoft.Practices.Prism.PubSubEvents..::.DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

See Also
--------

<span id="seeAlsoToggle"></span>
[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
