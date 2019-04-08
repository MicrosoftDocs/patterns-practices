---
TOCTitle: 'EventSubscription(TPayload) Class'
Title: 'EventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1'
ms:mtpsurl: 'eventsubscription-tpayload-class-mspp-pubsubevents.md'
---


# EventSubscription&lt;TPayload&gt; Class

Provides a way to retrieve a [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) to execute an action depending on the value of a second filter predicate that returns true if the action should execute.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)


## Syntax

```C#
public class EventSubscription<TPayload> : IEventSubscription

```

### Type Parameters

*TPayload*<br/>
The type to use for the generic [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
Microsoft.Practices.Prism.PubSubEvents.EventSubscription&lt;TPayload&gt;<br/>
[Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

## See Also

EventSubscription&lt;TPayload&gt; Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)

# EventSubscription(Of TPayload) Class

Provides a way to retrieve a [Delegate](http://msdn.microsoft.com/en-us/library/y22acf51) to execute an action depending on the value of a second filter predicate that returns true if the action should execute.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)


## Syntax

```VB
'Declaration
Public Class EventSubscription(Of TPayload)
	Implements IEventSubscription
```
### Type Parameters

*TPayload*<br/>
The type to use for the generic [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
Microsoft.Practices.Prism.PubSubEvents.EventSubscription(Of TPayload)<br/>
[Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription(Of TPayload)](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription(Of TPayload)](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

## See Also

EventSubscription(Of TPayload) Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)