---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'compositepresentationevent-tpayload-contains-method-action-tpayload-mspp-events.md'
---

# CompositePresentationEvent&lt;TPayload&gt;.Contains Method (Action&lt;TPayload&gt;)

Returns **truetrue** (**True** in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax
```C#
public virtual bool Contains(
	Action<TPayload> subscriber
)
```
```VB
'Declaration
Public Overridable Function Contains ( 
	subscriber As Action(Of TPayload)
) As Boolean
```
### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)&gt;

The [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if there is an [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) that matches; otherwise **falsefalse** (**False** in Visual Basic).

## See Also
[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)

[CompositePresentationEvent&lt;TPayload&gt; Members](/patterns-practices/reference/compositepresentationevent-tpayload-members-mspp-events)

[Contains Overload](/patterns-practices/reference/compositepresentationevent-tpayload-contains-method-mspp-events)

[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)
