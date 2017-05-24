---
TOCTitle: SubscriptionToken Constructor
Title: 'SubscriptionToken Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken.\#ctor(System.Action{Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736261(v=PandP.50)'
---

# SubscriptionToken Constructor

Initializes a new instance of [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken(
	Action<SubscriptionToken> unsubscribeAction
)
```

### Parameters

*unsubscribeAction*<br/> 
		
		Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)<[SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken)>

```VB
'Declaration
Public Sub New ( 
	unsubscribeAction As Action(Of SubscriptionToken)
)
```
### Parameters

*unsubscribeAction*<br/> 
		
		Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken))

## See Also

[SubscriptionToken Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken)

SubscriptionToken Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents)
