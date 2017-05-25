---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'compositepresentationevent-tpayload-contains-method-action-tpayload-mspp-events.md'
---

Prism Class Library

CompositePresentationEvent&lt;TPayload&gt;.Contains Method (Action&lt;TPayload&gt;)
=====================================================================================================================

Returns **truetrue** (**True** in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.Events](mspp-events-namespace.md)

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](compositepresentationevent-tpayload-class-mspp-events.md)&gt;

The [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if there is an [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) that matches; otherwise **falsefalse** (**False** in Visual Basic).

See Also
--------


[CompositePresentationEvent&lt;TPayload&gt; Class](compositepresentationevent-tpayload-class-mspp-events.md)

[CompositePresentationEvent&lt;TPayload&gt; Members](compositepresentationevent-tpayload-members-mspp-events.md)

[Contains Overload](compositepresentationevent-tpayload-contains-method-mspp-events.md)

[Microsoft.Practices.Prism.Events Namespace](mspp-events-namespace.md)
