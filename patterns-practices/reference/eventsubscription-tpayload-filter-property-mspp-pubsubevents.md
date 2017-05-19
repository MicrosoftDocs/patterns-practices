---
TOCTitle: Filter Property
Title: 'EventSubscription(TPayload).Filter Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Filter'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736196(v=PandP.50)'
---

Prism Class Library

EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).Filter Property
====================================================================

Gets the target [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz) that is referenced by the [IDelegateReference](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public Predicate&lt;TPayload&gt; Filter { get; }Public ReadOnly Property Filter As Predicate(Of TPayload) Get
### Property Value

Type: [Predicate](http://msdn2.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601)&gt;)&gt;)
An [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz) or nullNothingnullptra null reference (Nothing in Visual Basic) if the referenced target is not alive.

See Also
--------


[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
