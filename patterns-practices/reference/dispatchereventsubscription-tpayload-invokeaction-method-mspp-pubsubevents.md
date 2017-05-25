---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736289(v=PandP.50)'
---

Prism Class Library

# DispatcherEventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

### Syntax
```C#
public override void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

### Parameters

_action_
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)&gt;
The action to execute.

_argument_  
Type: [TPayload](https://msdn.microsoft.com/en-us/library/dn736239(v=pandp.50))
The payload to pass action while invoking it.


# DispatcherEventSubscription(Of TPayload).InvokeAction Method

Invokes the specified [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

### Syntax
```VB
'Declaration
Public Overrides Sub InvokeAction ( 
	action As Action(Of TPayload),
	argument As TPayload
)
)
```

### Parameters

_action_
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/dn736239(v=pandp.50)))
The action to execute.

_argument_  
Type: [TPayload](https://msdn.microsoft.com/en-us/library/dn736239(v=pandp.50))
The payload to pass action while invoking it.


## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn736239(v=pandp.50))

DispatcherEventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
