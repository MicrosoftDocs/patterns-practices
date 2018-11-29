---
TOCTitle: Contains Method
Title: 'EventBase.Contains Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.Contains(Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken)'
ms:mtpsurl: 'eventbase-contains-method-mspp-pubsubevents.md'
---

# EventBase.Contains Method

Returns **truetrue** (**True** in Visual Basic) if there is a subscriber matching [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool Contains(
	SubscriptionToken token
)
```


#### Parameters

*token*  
Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)  
The [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) returned by [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents) while subscribing to the event.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)  
**Truetrue** (**True** in Visual Basic) if there is a [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that matches; otherwise **Falsefalse** (**False** in Visual Basic).

```VB
'Declaration
Public Overridable Function Contains ( 
	token As SubscriptionToken
) As Boolean
)
```

#### Parameters

*token*  
Type: [Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)  
The [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) returned by [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents) while subscribing to the event.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)  
**truetrue** (**True** in Visual Basic) if there is a [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents) that matches; otherwise **falsefalse** (**False** in Visual Basic).

## See Also

[EventBase Class](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)  
EventBase Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)  
