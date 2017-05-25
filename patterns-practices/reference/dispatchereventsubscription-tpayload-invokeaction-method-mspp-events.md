---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405775(v=PandP.50)'
---


# DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;).InvokeAction Method

Invokes the specified [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public override void InvokeAction( Action&lt;TPayload&gt; action, TPayload argument )Public Overrides Sub InvokeAction ( action As Action(Of TPayload), argument As TPayload )

### Parameters

action  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)&gt;)&gt;)
The action to execute.

argument  
Type: [TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)
The payload to pass action while invoking it.

## See Also

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
