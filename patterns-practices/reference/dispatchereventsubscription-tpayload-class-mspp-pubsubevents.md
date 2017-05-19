---
TOCTitle: 'DispatcherEventSubscription(TPayload) Class'
Title: 'DispatcherEventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736239(v=PandP.50)'
---

Prism Class Library

DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class
================================================================

Extends [EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601) to invoke the [Action](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action) delegate in a specific [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public class DispatcherEventSubscription&lt;TPayload&gt; : EventSubscription&lt;TPayload&gt; Public Class DispatcherEventSubscription(Of TPayload) Inherits EventSubscription(Of TPayload)
Type Parameters
---------------

<span id="templatesToggle"></span>
TPayload  
The type to use for the generic [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz) types.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.PubSubEvents.EventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601)&lt;(Of &lt;(TPayload&gt;)&gt;)
    Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)

See Also
--------


[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
