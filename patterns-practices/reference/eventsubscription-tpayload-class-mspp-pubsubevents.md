---
TOCTitle: 'EventSubscription(TPayload) Class'
Title: 'EventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1'
ms:mtpsurl: 'eventsubscription-tpayload-class-mspp-pubsubevents.md'
---


# EventSubscription&lt;TPayload&gt; Class

Provides a way to retrieve a [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) to execute an action depending on the value of a second filter predicate that returns true if the action should execute.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](mspp-pubsubevents-namespace.md)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)


## Syntax


```C#
public class EventSubscription<TPayload> : IEventSubscription

```

```VB
'Declaration
Public Class EventSubscription(Of TPayload)
	Implements IEventSubscription
```

### Type Parameters


*TPayload*  

The type to use for the generic [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)

Microsoft.Practices.Prism.PubSubEvents.EventSubscription&lt;TPayload&gt;

[Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription&lt;TPayload&gt;](backgroundeventsubscription-tpayload-class-mspp-pubsubevents.md)

[Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription&lt;TPayload&gt;](dispatchereventsubscription-tpayload-class-mspp-pubsubevents.md)

## See Also

EventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](mspp-pubsubevents-namespace.md)