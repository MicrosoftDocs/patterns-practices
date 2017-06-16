---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'PubSubEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'pubsubevent-tpayload-contains-method-action-tpayload-mspp-pubsubevents.md'
---

# PubSubEvent&lt;TPayload&gt;.Contains Method (Action&lt;TPayload&gt;)

Returns **truetrue** (**True** in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual bool Contains(
	Action<TPayload> subscriber
)
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)&gt;  
The [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**truetrue** (**True** in Visual Basic) if there is an [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) that matches; otherwise **falsefalse** (**False** in Visual Basic).

## See Also

[PubSubEvent&lt;TPayload&gt; Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)  
PubSubEvent&lt;TPayload&gt; Members  
[Contains Overload](/patterns-practices/reference/pubsubevent-tpayload-contains-method-mspp-pubsubevents)  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)  

# PubSubEvent(Of TPayload).Contains Method (Action(Of TPayload))

Returns **Truetrue** (**True** in Visual Basic) if there is a subscriber matching [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Function Contains ( 
	subscriber As Action(Of TPayload)
) As Boolean
```

### Parameters

*subscriber*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents))  
The [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
**Truetrue** (**True** in Visual Basic) if there is an [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) that matches; otherwise **Falsefalse** (**False** in Visual Basic).

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)  
PubSubEvent(Of TPayload) Members  
[Contains Overload](/patterns-practices/reference/pubsubevent-tpayload-contains-method-mspp-pubsubevents)  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)  