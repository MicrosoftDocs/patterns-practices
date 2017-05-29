---
TOCTitle: GetExecutionStrategy Method
Title: 'IEventSubscription.GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.IEventSubscription.GetExecutionStrategy'
ms:mtpsurl: 'ieventsubscription-getexecutionstrategy-method-mspp-pubsubevents.md'
---
# IEventSubscription.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
Action<Object[]> GetExecutionStrategy()
```

```VB
'Declaration
Function GetExecutionStrategy As Action(Of Object())
```

#### Return Value

Type: [Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt; [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)[]&gt;

An [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **Nothinga** null reference (**Nothing** in Visual Basic) if the [IEventSubscription](ieventsubscription-interface-mspp-pubsubevents.md) is no longer valid.

IEventSubscription.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
Action&lt;Object[]&gt; GetExecutionStrategy()Function GetExecutionStrategy As Action(Of Object())
### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;(array&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;&gt;)&gt;)
An [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or nullNothingnullptra null reference (Nothing in Visual Basic) if the [IEventSubscription](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription) is no longer valid.
## See Also
[IEventSubscription Interface](ieventsubscription-interface-mspp-pubsubevents.md)

[IEventSubscription Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription)
IEventSubscription Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)
