---
TOCTitle: Subscriptions Property
Title: 'EventBase.Subscriptions Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventBase.Subscriptions'
ms:mtpsurl: 'eventbase-subscriptions-property-mspp-pubsubevents.md'
---

# EventBase.Subscriptions Property 

Gets the list of current subscriptions.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected ICollection<IEventSubscription> Subscriptions { get; }
```

### Property Value

Type: [ICollection](http://msdn.microsoft.com/en-us/library/92t2ye13)&lt;[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)&gt;

The current subscribers.

## Syntax

```VB
'Declaration
Protected ReadOnly Property Subscriptions As ICollection(Of IEventSubscription)
	Get
```

### Property Value

Type: [ICollection](http://msdn.microsoft.com/en-us/library/92t2ye13)(Of [IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents))

The current subscribers.



## See Also

[EventBase Class](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)

EventBase Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)
