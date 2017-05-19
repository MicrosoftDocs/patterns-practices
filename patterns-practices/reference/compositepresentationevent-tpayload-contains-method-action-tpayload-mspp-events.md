---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405766(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;TPayload&gt;.Contains Method (Action&lt;TPayload&gt;)
=====================================================================================================================

Returns **truetrue** (**True** in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

Syntax
------

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

#### Parameters

*subscriber*  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))&gt;

The [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)

**truetrue** (**True** in Visual Basic) if there is an [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) that matches; otherwise **falsefalse** (**False** in Visual Basic).

See Also
--------


[CompositePresentationEvent&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/gg431412(v=pandp.50))

[CompositePresentationEvent&lt;TPayload&gt; Members](https://msdn.microsoft.com/en-us/library/gg430765(v=pandp.50))

[Contains Overload](https://msdn.microsoft.com/en-us/library/gg419056(v=pandp.50))

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.events(v=pandp.50))
