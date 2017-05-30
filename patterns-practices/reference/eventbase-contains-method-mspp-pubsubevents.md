---
TOCTitle: Contains Method
Title: 'EventBase.Contains Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.Contains(Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken)'
ms:mtpsurl: 'eventbase-contains-method-mspp-pubsubevents.md'
---

# EventBase.Contains Method

Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [SubscriptionToken](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public virtual bool Contains( SubscriptionToken token )Public Overridable Function Contains ( token As SubscriptionToken ) As Boolean

### Parameters

token  
Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken)
The [SubscriptionToken](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken) returned by [EventBase](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase) while subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if there is a [SubscriptionToken](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.subscriptiontoken) that matches; otherwise falseFalsefalsefalse (False in Visual Basic).

## See Also
[EventBase Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.eventbase)

[EventBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
