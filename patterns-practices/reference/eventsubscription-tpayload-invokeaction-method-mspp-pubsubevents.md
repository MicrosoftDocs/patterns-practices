---
TOCTitle: InvokeAction Method
Title: 'EventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'eventsubscription-tpayload-invokeaction-method-mspp-pubsubevents.md'
---

# EventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) synchronously when not overridden.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```


### Parameters

*action*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The action to execute.

*argument*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The payload to pass action while invoking it.

## Exceptions

| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if action is null. |

## See Also

[EventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)<br/>
EventSubscription&lt;TPayload&gt; 

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>

# EventSubscription(Of TPayload).InvokeAction Method 

Invokes the specified [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) synchronously when not overridden.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Sub InvokeAction ( 
	action As Action(Of TPayload),
	argument As TPayload
)
```


### Parameters

*action*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents/eventsubscription-tpayload-class-mspp-pubsubevents))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The action to execute.

*argument*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [TPayload](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The payload to pass action while invoking it.

## Exceptions

| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if action is null. |

## See Also

[EventSubscription(Of TPayload) Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)<br/>
EventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)<br/>