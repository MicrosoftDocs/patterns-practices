---
TOCTitle: 'PubSubEvent(TPayload) Class'
Title: 'PubSubEvent(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'pubsubevent-tpayload-class-mspp-pubsubevents.md'
---


# PubSubEvent&lt;TPayload&gt; Class

Defines a class that manages publication and subscription to events.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    public class PubSubEvent<TPayload> : EventBase
``` 

### Type Parameters

TPayload  
The type of message that will be passed to the subscribers.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

[Microsoft.Practices.Prism.PubSubEvents.EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase)

Microsoft.Practices.Prism.PubSubEvents.PubSubEvent&lt;TPayload&gt;

# PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class

Defines a class that manages publication and subscription to events.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
    'Declaration
Public Class PubSubEvent(Of TPayload)
	Inherits EventBase
``` 

### Type Parameters

TPayload  
The type of message that will be passed to the subscribers.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

[Microsoft.Practices.Prism.PubSubEvents.EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase)

Microsoft.Practices.Prism.PubSubEvents.PubSubEvent(Of TPayload)

## See Also

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)