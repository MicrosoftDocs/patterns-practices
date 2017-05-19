---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'EventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736138(v=PandP.50)'
---

Prism Class Library

EventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;) Method
====================================================================

Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public TEventType GetEvent&lt;TEventType&gt;() where TEventType : new(), EventBase Public Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
Type Parameters
---------------

<span id="templatesToggle"></span>
TEventType  
The type of event to get. This must inherit from [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase).

### Return Value

Type: TEventType
A singleton instance of an event object of type TEventType.
### Implements

[IEventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;)()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.ieventaggregator.getevent%60%601)

See Also
--------


[EventAggregator Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventaggregator)

[EventAggregator Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventaggregator)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
