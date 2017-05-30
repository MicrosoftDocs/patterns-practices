---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'PubSubEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'pubsubevent-tpayload-contains-method-action-tpayload-mspp-pubsubevents.md'
---

# PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Contains Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;))

Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax
public virtual bool Contains( Action&lt;TPayload&gt; subscriber )Public Overridable Function Contains ( subscriber As Action(Of TPayload) ) As Boolean

### Parameters

subscriber  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601)&gt;)&gt;)
The [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if there is an [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) that matches; otherwise falseFalsefalsefalse (False in Visual Basic).

## See Also
[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601)

[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Contains Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.pubsubevents.pubsubevent%601.contains)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
