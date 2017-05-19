---
TOCTitle: InternalPublish Method
Title: 'EventBase.InternalPublish Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.InternalPublish(System.Object[])'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736108(v=PandP.50)'
---

Prism Class Library

EventBase..::.InternalPublish Method
====================================

Calls all the execution strategies exposed by the list of [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual void InternalPublish( params Object[] arguments )Protected Overridable Sub InternalPublish ( ParamArray arguments As Object() )
#### Parameters

arguments  
Type: array&lt;[System..::.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&gt;[]()[]
The arguments that will be passed to the listeners.

Remarks
-------

<span id="remarksToggle"></span>Before executing the strategies, this class will prune all the subscribers from the list that return a nullNothingnullptra null reference (Nothing in Visual Basic)[Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) when calling the [GetExecutionStrategy()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.ieventsubscription.getexecutionstrategy) method.

See Also
--------

<span id="seeAlsoToggle"></span>
[EventBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase)

[EventBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
