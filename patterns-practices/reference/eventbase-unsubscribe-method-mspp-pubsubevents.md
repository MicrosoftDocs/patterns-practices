---
TOCTitle: Unsubscribe Method
Title: 'EventBase.Unsubscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.Unsubscribe(Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken)'
ms:mtpsurl: 'eventbase-unsubscribe-method-mspp-pubsubevents.md'
---

# EventBase.Unsubscribe Method

Removes the subscriber matching the [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public virtual void Unsubscribe( SubscriptionToken token )Public Overridable Sub Unsubscribe ( token As SubscriptionToken )

### Parameters

token  
Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken)
The [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken) returned by [EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase) while subscribing to the event.

## See Also
[EventBase Class](/patterns-practices/reference/mspp-mvvm-namespace.eventbase)

[EventBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
