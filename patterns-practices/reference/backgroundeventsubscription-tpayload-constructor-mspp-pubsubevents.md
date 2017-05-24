---
TOCTitle: 'BackgroundEventSubscription(TPayload) Constructor'
Title: 'BackgroundEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736142(v=PandP.50)'
---

Prism Class Library
# BackgroundEventSubscription(Of TPayload) Constructor

Creates a new instance of [BackgroundEventSubscription(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn683933(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))<br>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New (
	actionReference As IDelegateReference,
	filterReference As IDelegateReference
)
```

#### Parameters

*actionReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50))

A reference to a delegate of type [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

*filterReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50))

A reference to a delegate of type [Predicate(Of T)](http://msdn2.microsoft.com/en-us/library/bfcke1bz).

## Exceptions

<table responsive="true" summary="table">
<tbody>
<tr responsive="true">
<th class="exceptionNameColumn" scope="col">Exception</th>
<th class="exceptionConditionColumn" scope="col">Condition</th>
</tr>
<tr>
<td data-th="Exception">
<a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">System<span xmlns="">.</span>ArgumentNullException</a>
</td>
<td data-th="Condition">When <em>actionReference</em> or are <strong>Nothing</strong>a null reference (<strong>Nothing</strong> in Visual Basic).</td>
</tr>
<tr>
<td data-th="Exception">
<a href="http://msdn2.microsoft.com/en-us/library/3w1b3114" target="_blank">System<span xmlns="">.</span>ArgumentException</a>
</td>
<td data-th="Condition">When the target of <em>actionReference</em> is not of type <a href="http://msdn2.microsoft.com/en-us/library/018hxwa8" target="_blank">Action<span xmlns="">(Of </span>T<span xmlns="">)</span>
</a>, or the target of <em>filterReference</em> is not of type <a href="http://msdn2.microsoft.com/en-us/library/bfcke1bz" target="_blank">Predicate<span xmlns="">(Of </span>T<span xmlns="">)</span>
</a>.</td>
</tr>
</tbody>
</table>

## See Also

[BackgroundEventSubscription(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn683933(v=pandp.50))

BackgroundEventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

Prism Class Library
# BackgroundEventSubscription&lt;TPayload&gt; Constructor

Creates a new instance of [BackgroundEventSubscription&lt;TPayload&gt;](https://msdn.microsoft.com/en-us/library/dn683933(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public BackgroundEventSubscription(
	IDelegateReference actionReference,
	IDelegateReference filterReference
)
```

#### Parameters

*actionReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50))

A reference to a delegate of type [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8).

*filterReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.idelegatereference(v=pandp.50))

A reference to a delegate of type [Predicate&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/bfcke1bz).

## [Exceptions]()

<table responsive="true" summary="table">
<tbody>
<tr responsive="true">
<th class="exceptionNameColumn" scope="col">Exception</th>
<th class="exceptionConditionColumn" scope="col">Condition</th>
</tr>
<tr>
<td data-th="Exception">
<a href="http://msdn2.microsoft.com/en-us/library/27426hcy" target="_blank">System<span xmlns="">.</span>ArgumentNullException</a>
</td>
<td data-th="Condition">When <e>actionReference</em> or are <strong>null</strong>a null reference (<strong>Nothing</strong> in Visual Basic).
</td>
</tr>
<tr>
<td data-th="Exception">
<a href="http://msdn2.microsoft.com/en-us/library/3w1b3114" target="_blank">System<span xmlns="">.</span>ArgumentException</a>
</td>
<td data-th="Condition">When the target of <em>actionReference</em> is not of type <a href="http://msdn2.microsoft.com/en-us/library/018hxwa8" target="_blank">Action&lt;T&gt;</a>, or the target of <em>filterReference</em> is not of type <a href="http://msdn2.microsoft.com/en-us/library/bfcke1bz" target="_blank">Predicate<span xmlns="">Predicate&lt;T&gt;</a>.</td>
</tr>
</tbody>
</table>

## See Also

[BackgroundEventSubscription&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn683933(v=pandp.50))
BackgroundEventSubscription&lt;TPayload&gt; Members
[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

