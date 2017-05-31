---
TOCTitle: Filter Property
Title: 'EventSubscription(TPayload).Filter Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Filter'
ms:mtpsurl: 'eventsubscription-tpayload-filter-property-mspp-pubsubevents.md'
---

# EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).Filter Property

Gets the target [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz) that is referenced by the [IDelegateReference](/patterns-practices/reference/mspp-mvvm-namespace.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public Predicate&lt;TPayload&gt; Filter { get; }Public ReadOnly Property Filter As Predicate(Of TPayload) Get
### Property Value

Type: [Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;(Of &lt;([TPayload](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601)&gt;)&gt;)
An [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz) or nullNothingnullptra null reference (Nothing in Visual Basic) if the referenced target is not alive.

## See Also
[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](/patterns-practices/reference/mspp-mvvm-namespace.eventsubscription%601)

[EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.eventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)
