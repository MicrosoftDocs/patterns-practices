---
TOCTitle: InternalSubscribe Method
Title: 'EventBase.InternalSubscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.InternalSubscribe(Microsoft.Practices.Prism.PubSubEvents.IEventSubscription)'
ms:mtpsurl: 'eventbase-internalsubscribe-method-mspp-pubsubevents.md'
---

# EventBase.InternalSubscribe Method

Adds the specified [IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents) to the subscribers' collection.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
protected virtual SubscriptionToken InternalSubscribe(
	IEventSubscription eventSubscription
)
```

```VB
'Declaration
Protected Overridable Function InternalSubscribe ( 
	eventSubscription As IEventSubscription
) As SubscriptionToken
```

### Parameters

*eventSubscription*<br/>
Type: [Microsoft.Practices.Prism.PubSubEvents.IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)<br/>
The subscriber.

### Return Value

Type: [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)<br/>
The [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that uniquely identifies every subscriber.

## Remarks

Adds the subscription to the internal list and assigns it a new [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).

## See Also

[EventBase Class](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)<br/>
EventBase Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>