---
TOCTitle: GetExecutionStrategy Method
Title: 'EventSubscription(TPayload).GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.GetExecutionStrategy'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736174(v=PandP.50)'
---

Prism Class Library

EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).GetExecutionStrategy Method
================================================================================

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual Action&lt;Object[]&gt; GetExecutionStrategy()Public Overridable Function GetExecutionStrategy As Action(Of Object())
#### Return Value

Type: [Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;(array&lt;[Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;&gt;)&gt;)
An [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or nullNothingnullptra null reference (Nothing in Visual Basic) if the [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription) is no longer valid.
#### Implements

[IEventSubscription.GetExecutionStrategy()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.ieventsubscription.getexecutionstrategy)

Remarks
-------

<span id="remarksToggle"></span> If [Action](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action) or [Filter](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.filter) are no longer valid because they were garbage collected, this method will return nullNothingnullptra null reference (Nothing in Visual Basic). Otherwise it will return a delegate that evaluates the [Filter](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.filter) and if it returns trueTruetruetrue (True in Visual Basic) will then call [InvokeAction(Action&lt;(Of &lt;(TPayload&gt;)&gt;), TPayload)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventsubscription%601.invokeaction(system.action%7b%600%7d%2c%600)). The returned delegate holds hard references to the [Action](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action) and [Filter](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.filter) target [delegates](http://msdn2.microsoft.com/en-us/library/y22acf51). As long as the returned delegate is not garbage collected, the [Action](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action) and [Filter](https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.filter) references delegates won't get collected either.

See Also
--------

<span id="seeAlsoToggle"></span>
[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
