---
TOCTitle: 'GetEvent(TEventType) Method'
Title: 'IEventAggregator.GetEvent(TEventType) Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.IEventAggregator.GetEvent\`\`1'
ms:mtpsurl: 'ieventaggregator-getevent-teventtype-method-mspp-pubsubevents.md'
---

# IEventAggregator.GetEvent&lt;TEventType&gt; Method

Gets an instance of an event type.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
TEventType GetEvent<TEventType>()
where TEventType : new(), EventBase
```

## Type Parameters

*TEventType*  

The type of event to get.

### Return Value

Type: TEventType

An instance of an event object of type TEventType.

## See Also

[IEventAggregator Interface](/patterns-practices/reference/bindablebase-class-mspp-mvvm)<br/>
IEventAggregator Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)<br/>

# IEventAggregator.GetEvent(Of TEventType) Method

Gets an instance of an event type.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB  
'Declaration
Function GetEvent(Of TEventType As {New, EventBase}) As TEventType
```

##Type Parameters

*TEventType*  

The type of event to get.

### Return Value

Type: TEventType

An instance of an event object of type TEventType.

## See Also

[IEventAggregator Interface](/patterns-practices/reference/bindablebase-class-mspp-mvvm)<br/>
IEventAggregator Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)