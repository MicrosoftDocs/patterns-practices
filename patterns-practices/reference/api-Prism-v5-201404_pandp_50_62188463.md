---
TOCTitle: InvokeAction Method
Title: 'EventSubscription(TPayload).InvokeAction Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.InvokeAction(System.Action{\`0},\`0)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683965(v=PandP.50)'
---

# EventSubscription&lt;TPayload&gt;.InvokeAction Method

Invokes the specified [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) synchronously when not overridden.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public virtual void InvokeAction(
	Action<TPayload> action,
	TPayload argument
)
```

#### Parameters

*action*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The action to execute.

*argument*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The payload to pass action while invoking it.

## Exceptions

| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if action is null. |

## See Also

[EventSubscription&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription&lt;TPayload&gt; 

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

# EventSubscription(Of TPayload).InvokeAction Method 

Invokes the specified [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) synchronously when not overridden.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Overridable Sub InvokeAction ( 
	action As Action(Of TPayload),
	argument As TPayload
)
```

#### Parameters

*action*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50)))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The action to execute.

*argument*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [TPayload](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The payload to pass action while invoking it.

## Exceptions

| Exception                                                                             | Condition                                                                                                  |
|---------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | An [ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) is thrown if action is null. |

## See Also

[EventSubscription(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
