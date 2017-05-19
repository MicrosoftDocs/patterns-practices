---
TOCTitle: InternalSubscribe Method
Title: 'EventBase.InternalSubscribe Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.InternalSubscribe(Microsoft.Practices.Prism.PubSubEvents.IEventSubscription)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736126(v=PandP.50)'
---

Prism Class Library

EventBase.InternalSubscribe Method
======================================

Adds the specified [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription) to the subscribers' collection.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>protected virtual SubscriptionToken InternalSubscribe( IEventSubscription eventSubscription )Protected Overridable Function InternalSubscribe ( eventSubscription As IEventSubscription ) As SubscriptionToken
#### Parameters

eventSubscription  
Type: [Microsoft.Practices.Prism.PubSubEvents.IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription)
The subscriber.

#### Return Value

Type: [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken)
The [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken) that uniquely identifies every subscriber.

Remarks
-------

<span id="remarksToggle"></span> Adds the subscription to the internal list and assigns it a new [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken).

See Also
--------


[EventBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase)

[EventBase Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
