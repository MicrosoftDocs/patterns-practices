---
TOCTitle: Contains Method
Title: 'EventBase.Contains Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.Contains(Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken)'
ms:mtpsurl: 'eventbase-contains-method-mspp-pubsubevents.md'
---

# EventBase.Contains Method

Returns **Truetrue** (**True** in Visual Basic) if there is a subscriber matching [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool Contains(
	SubscriptionToken token
)
```
```VB
'Declaration
Public Overridable Function Contains ( 
	token As SubscriptionToken
) As Boolean
)
```

#### Parameters

*token*

Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50))

The [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)) returned by [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50)) while subscribing to the event.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if there is a [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)) that matches; otherwise **falsefalse** (**False** in Visual Basic).

## See Also

[EventBase Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50))

EventBase Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

