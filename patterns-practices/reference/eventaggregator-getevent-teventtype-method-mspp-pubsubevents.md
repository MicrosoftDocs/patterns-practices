---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'EventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'eventaggregator-getevent-teventtype-method-mspp-pubsubevents.md'
---


# EventAggregator.GetEvent&lt;TEventType&gt; Method

Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

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

The type of event to get. This must inherit from [EventBase](eventbase-class-mspp-pubsubevents.md).

### Return Value

Type: TEventType

A singleton instance of an event object of type TEventType.


#### Implements

[IEventAggregator.GetEvent(Of TEventType)()](ieventaggregator-getevent-teventtype-method-mspp-pubsubevents.md) 
=======
### Implements

[IEventAggregator.GetEvent&lt;(Of &lt;(TEventType&gt;)&gt;)()()()](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventaggregator.getevent%60%601)


## See Also


[EventAggregator Class](eventaggregator-class-mspp-pubsubevents.md)
=======

[EventAggregator Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventaggregator)


EventAggregator Members 

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)
