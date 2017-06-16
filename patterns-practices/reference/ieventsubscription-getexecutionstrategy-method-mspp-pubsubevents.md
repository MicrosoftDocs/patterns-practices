---
TOCTitle: GetExecutionStrategy Method
Title: 'IEventSubscription.GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.IEventSubscription.GetExecutionStrategy'
ms:mtpsurl: 'ieventsubscription-getexecutionstrategy-method-mspp-pubsubevents.md'
---

# IEventSubscription.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
Action<Object[]> GetExecutionStrategy()
```
#### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)[]&gt;

An [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **null**a null reference (**Nothing** in Visual Basic) if the [IEventSubscription ](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)is no longer valid.

## Syntax

```VB
'Declaration
Function GetExecutionStrategy As Action(Of Object())
```

#### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)())

An [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **Nothing**a null reference (**Nothing** in Visual Basic) if the [IEventSubscription ](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)is no longer valid.

## See Also

[IEventSubscription Interface](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)  
IEventSubscription Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)