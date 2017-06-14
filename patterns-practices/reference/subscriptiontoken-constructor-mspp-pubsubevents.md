---
TOCTitle: SubscriptionToken Constructor
Title: 'SubscriptionToken Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken.\#ctor(System.Action{Microsoft.Practices.Prism.PubSubEvents.SubscriptionToken})'
ms:mtpsurl: 'subscriptiontoken-constructor-mspp-pubsubevents.md'
---

# SubscriptionToken Constructor

Initializes a new instance of [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)<br/>
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public SubscriptionToken(
	Action<SubscriptionToken> unsubscribeAction
)
```

### Parameters

*unsubscribeAction*<br/> 
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)&gt;

```VB
'Declaration
Public Sub New ( 
	unsubscribeAction As Action(Of SubscriptionToken)
)
```
### Parameters

*unsubscribeAction*<br/> 
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents))

## See Also

[SubscriptionToken Class](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents(v=pandp.50))<br/>
SubscriptionToken Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)