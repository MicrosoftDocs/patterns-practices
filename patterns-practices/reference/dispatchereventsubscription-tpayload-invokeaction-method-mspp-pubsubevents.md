---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-invokeaction-method-mspp-pubsubevents.md'
---


# DispatcherEventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

### Syntax

```C#
public override void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

### Parameters

*action*

Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)&gt;
The action to execute.

*argument*
  
Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

The payload to pass action while invoking it.

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)<br/>
DispatcherEventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>


# DispatcherEventSubscription(Of TPayload).InvokeAction Method

Invokes the specified [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [SynchronizationContext](http://msdn2.microsoft.com/en-us/library/wx31754f).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) <br/>
**Version:** 1.0.0.0 (1.0.0.0)

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

*action*

Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents))

The action to execute.

*argument*

Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)

The payload to pass action while invoking it.


## See Also

[DispatcherEventSubscription(Of TPayload) Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)<br/>
DispatcherEventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)<br/>
