---
TOCTitle: 'BackgroundEventSubscription(TPayload) Class'
Title: 'BackgroundEventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1'
ms:mtpsurl: 'backgroundeventsubscription-tpayload-class-mspp-pubsubevents.md'
---

# BackgroundEventSubscription&lt;TPayload&gt; Class

Extends [EventSubscription&lt;TPayload&gt;](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents) to invoke the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) delegate in a background thread.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    public class BackgroundEventSubscription<TPayload> : EventSubscription<TPayload>
```

### Type Parameters

*TPayload*  
    The type to use for the generic [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/> 
[Microsoft.Practices.Prism.PubSubEvents.EventSubscription](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)&lt;TPayload&gt;  
Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription&lt;TPayload&gt;

## See Also

BackgroundEventSubscription&lt;TPayload&gt; Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)

# BackgroundEventSubscription(Of TPayload) Class

Extends [EventSubscription(Of TPayload)](/eventsubscription-tpayload-class-mspp-pubsubevents) to invoke the [Action](/eventsubscription-tpayload-action-property-mspp-pubsubevents) delegate in a background thread.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
    'Declaration
    Public Class BackgroundEventSubscription(Of TPayload)
	   Inherits EventSubscription(Of TPayload)
```

### Type Parameters

*TPayload*  
    The type to use for the generic [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.PubSubEvents.EventSubscription](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)(Of TPayload)  
Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription(Of TPayload)

## See Also

BackgroundEventSubscription(Of TPayload) Members<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)