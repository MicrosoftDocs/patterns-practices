---
TOCTitle: InvokeAction Method
Title: 'BackgroundEventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'backgroundeventsubscription-tpayload-invokeaction-method-mspp-pubsubevents.md'
---

# BackgroundEventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) in an asynchronous thread by using a [ThreadPool](http://msdn.microsoft.com/en-us/library/y5htx827).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
public override void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

### Parameters

*action*  

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://review.docs.microsoft.com/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents
)&gt;

The action to execute.

*argument*

Type: [TPayload](https://review.docs.microsoft.com/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents
)

The payload to pass action while invoking it.

## See Also

[BackgroundEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)<br/>
BackgroundEventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)<br/>


# BackgroundEventSubscription(Of TPayload).InvokeAction Method

Invokes the specified [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) in an asynchronous thread by using a [ThreadPool](http://msdn.microsoft.com/en-us/library/y5htx827).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) 

**Version:** 1.0.0.0 (1.0.0.0)

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

Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents))


The action to execute.

*argument*  

Type: [TPayload](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)

The payload to pass action while invoking it.

## See Also

[BackgroundEventSubscription(Of TPayload) Class](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)<br/>
BackgroundEventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)<br/>