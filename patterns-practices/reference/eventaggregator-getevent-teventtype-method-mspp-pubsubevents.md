---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'EventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'eventaggregator-getevent-teventtype-method-mspp-pubsubevents.md'
---


# EventAggregator.GetEvent&lt;TEventType&gt; Method

 Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance. 

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public TEventType GetEvent<TEventType>()
where TEventType : new(), EventBase
```

### Type Parameters

*TEventType*

The type of event to get. This must inherit from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).

### Return Value

Type: TEventType

A singleton instance of an event object of type TEventType.

#### Implements

[IEventAggregator.GetEvent&lt;TEventType&gt;()](/patterns-practices/reference/ieventaggregator-getevent-teventtype-method-mspp-pubsubevents)

# EventAggregator.GetEvent(Of TEventType) Method 

 Gets the single instance of the event managed by this EventAggregator. Multiple calls to this method with the same TEventType returns the same event instance. 

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB   
'Declaration
Public Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
```

### Type Parameters

*TEventType*

The type of event to get. This must inherit from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).

### Return Value

Type: TEventType

A singleton instance of an event object of type TEventType.

#### Implements

[IEventAggregator.GetEvent(Of TEventType)](/patterns-practices/reference/ieventaggregator-getevent-teventtype-method-mspp-pubsubevents)

## See Also

[EventAggregator Class](/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents)<br/>
EventAggregator Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)