---
TOCTitle: 'Unsubscribe Method (Action(TPayload))'
Title: 'CompositePresentationEvent(TPayload).Unsubscribe Method (Action(TPayload)) (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Unsubscribe(System.Action{\`0})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405773(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;).Unsubscribe Method (Action&lt;(Of &lt;(TPayload&gt;)&gt;))
========================================================================================================================

Removes the first subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public virtual void Unsubscribe( Action&lt;TPayload&gt; subscriber )Public Overridable Sub Unsubscribe ( subscriber As Action(Of TPayload) )

### Parameters

subscriber  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)&gt;)&gt;)
The [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) used when subscribing to the event.

See Also
--------


[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Unsubscribe Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.events.compositepresentationevent%601.unsubscribe)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
