---
TOCTitle: GetExecutionStrategy Method
Title: 'IEventSubscription.GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.IEventSubscription.GetExecutionStrategy'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736137(v=PandP.50)'
---

# IEventSubscription.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

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

An [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **Nothinga** null reference (**Nothing** in Visual Basic) if the [IEventSubscription](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.ieventsubscription(v=pandp.50)) is no longer valid.

## See Also

[IEventSubscription Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.ieventsubscription(v=pandp.50))

IEventSubscription Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
