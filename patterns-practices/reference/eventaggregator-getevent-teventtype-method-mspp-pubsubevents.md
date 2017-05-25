---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'EventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736138(v=PandP.50)'
---


# EventAggregator.GetEvent&lt;TEventType&gt; Method

Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public TEventType GetEvent<TEventType>()
where TEventType : new(), EventBase
```

```VB
'Declaration
Public Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
```
=======
Prism Class Library

EventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;) Method
====================================================================

Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public TEventType GetEvent&lt;TEventType&gt;() where TEventType : new(), EventBase Public Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
Type Parameters
---------------


### Type Parameters

*TEventType*

The type of event to get. This must inherit from [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50)).

### Return Value

Type: TEventType

A singleton instance of an event object of type TEventType.


#### Implements

[IEventAggregator.GetEvent(Of TEventType)()](https://msdn.microsoft.com/en-us/library/dn736172(v=pandp.50)) 
=======
### Implements

[IEventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;)()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventaggregator.getevent%60%601)


## See Also


[EventAggregator Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventaggregator(v=pandp.50))
=======

[EventAggregator Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventaggregator)


EventAggregator Members 

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
