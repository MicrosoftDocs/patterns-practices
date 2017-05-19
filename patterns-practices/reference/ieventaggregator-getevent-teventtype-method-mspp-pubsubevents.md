---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'IEventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.IEventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736172(v=PandP.50)'
---

Prism Class Library

IEventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;) Method
=====================================================================

Gets an instance of an event type.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>TEventType GetEvent&lt;TEventType&gt;() where TEventType : new(), EventBase Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
Type Parameters
---------------

<span id="templatesToggle"></span>
TEventType  
The type of event to get.

#### Return Value

Type: TEventType
An instance of an event object of type TEventType.

See Also
--------

<span id="seeAlsoToggle"></span>
[IEventAggregator Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventaggregator)

[IEventAggregator Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.ieventaggregator)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
