---
TOCTitle: 'Contains Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Contains Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Contains(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405766(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)..::.Contains Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;))
=====================================================================================================================

Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual bool Contains( Action&lt;TPayload&gt; subscriber )Public Overridable Function Contains ( subscriber As Action(Of TPayload) ) As Boolean
#### Parameters

subscriber  
Type: [System..::.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
The [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

#### Return Value

Type: [Boolean](http://msdn2.microsoft.com/en-us/library/a28wyd50)
trueTruetruetrue (True in Visual Basic) if there is an [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) that matches; otherwise falseFalsefalsefalse (False in Visual Basic).

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Contains Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.events.compositepresentationevent%601.contains)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
