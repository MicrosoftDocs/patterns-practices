---
TOCTitle: InvokeAction Method
Title: 'DispatcherEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-invokeaction-method-mspp-events.md'
---

# DispatcherEventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public override void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)&gt;  
The action to execute.

*argument*  
Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
The payload to pass action while invoking it.

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)<br/>
[DispatcherEventSubscription&lt;TPayload&gt; Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>

# DispatcherEventSubscription(Of TPayload).InvokeAction Method

Invokes the specified [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) asynchronously in the specified [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Overrides Sub InvokeAction ( 
	action As Action(Of TPayload),
	argument As TPayload
)
```

### Parameters

*action*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events))  
The action to execute.

*argument*  
Type: [TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
The payload to pass action while invoking it.

## See Also

[DispatcherEventSubscription(Of TPayload) Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)<br/>
[DispatcherEventSubscription(Of TPayload) Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>
