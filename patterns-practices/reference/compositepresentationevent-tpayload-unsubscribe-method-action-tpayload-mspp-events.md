---
TOCTitle: 'Unsubscribe Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Unsubscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Unsubscribe(System.Action{\`0})'
ms:mtpsurl: 'compositepresentationevent-tpayload-unsubscribe-method-action-tpayload-mspp-events.md'
---

# CompositePresentationEvent&lt;TPayload&gt;.Unsubscribe Method (Action&lt;TPayload&gt;)

Removes the first subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual void Unsubscribe(
	Action<TPayload> subscriber
)
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)&gt;  
The [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

## See Also

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Unsubscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-unsubscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  


# CompositePresentationEvent(Of TPayload).Unsubscribe Method (Action(Of TPayload))

Removes the first subscriber matching [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Sub Unsubscribe ( 
	subscriber As Action(Of TPayload)
)
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events))  
The [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

## See Also

[CompositePresentationEvent(Of TPayload) Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[CompositePresentationEvent(Of TPayload) Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)  
[Unsubscribe Overload](/patterns-practices/reference/compositepresentationevent-tpayload-unsubscribe-method-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  