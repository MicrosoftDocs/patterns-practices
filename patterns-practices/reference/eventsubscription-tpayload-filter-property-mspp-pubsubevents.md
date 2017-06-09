---
TOCTitle: Filter Property
Title: 'EventSubscription(TPayload).Filter Property (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'P:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.Filter'
ms:mtpsurl: 'eventsubscription-tpayload-filter-property-mspp-pubsubevents.md'
---

# EventSubscription&lt;TPayload&gt;.Filter Property

Gets the target [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) that is referenced by the [IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public Predicate<TPayload> Filter { get; }
```

### Property Value

Type: [Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)&lt;[TPayload]((https://review.docs.microsoft.com/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents
))&gt;

An [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) or **null**a null reference (**Nothing** in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)

EventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)



# EventSubscription(Of TPayload).Filter Property

Gets the target [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) that is referenced by the [IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public ReadOnly Property Filter As Predicate(Of TPayload)
	Get
```

### Property Value

Type: [Predicate](http://msdn.microsoft.com/en-us/library/bfcke1bz)(Of [TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents))

An [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) or **Nothing**a null reference (**Nothing** in Visual Basic) if the referenced target is not alive.

## See Also

[EventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)

EventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)