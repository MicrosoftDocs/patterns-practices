---
TOCTitle: Unsubscribe Method
Title: 'EventBase.Unsubscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.Unsubscribe(Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken)'
ms:mtpsurl: 'eventbase-unsubscribe-method-mspp-pubsubevents.md'
---

# EventBase.Unsubscribe Method

Removes the subscriber matching the [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void Unsubscribe(
	SubscriptionToken token
)
```
```VB
'Declaration
Public Overridable Sub Unsubscribe ( 
	token As SubscriptionToken
)
```

### Parameters

*token*  
Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)  
The [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) returned by [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents) while subscribing to the event.

## See Also

[EventBase Class](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)  
EventBase Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)