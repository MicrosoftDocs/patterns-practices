---
TOCTitle: GetExecutionStrategy Method
Title: 'EventSubscription(TPayload).GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.GetExecutionStrategy'
ms:mtpsurl: 'eventsubscription-tpayload-getexecutionstrategy-method-mspp-pubsubevents.md'
---

# EventSubscription&lt;TPayload&gt;.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
public virtual Action<Object[]> GetExecutionStrategy()
```

### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&lsqb;&rsqb;&gt;

An [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or nulla null reference (Nothing in Visual Basic) if the IEventSubscription is no longer valid.

### Implements

[IEventSubscription.GetExecutionStrategy&lpar;&rpar;](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription.getexecutionstrategy)

## Remarks

 If [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) or [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) are no longer valid because they were garbage collected, this method will return **null**a null reference (**Nothing** in Visual Basic). Otherwise it will return a delegate that evaluates the [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) and if it returns **truetrue** (**True** in Visual Basic) will then call [InvokeAction(Action<TPayload>, TPayload)](https://msdn.microsoft.com/en-us/library/dn683965(v=pandp.50)). The returned delegate holds hard references to the [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) and [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) target [delegates](http://msdn2.microsoft.com/en-us/library/y22acf51). As long as the returned delegate is not garbage collected, the [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) and [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) references delegates won't get collected either.

## See Also

[EventSubscription&lt;TPayload&gt; Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)


# EventSubscription(Of TPayload).GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB  
'Declaration
Public Overridable Function GetExecutionStrategy As Action(Of Object())
```

### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&lpar;&rpar;)

An [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **Nothing**a null reference (**Nothing** in Visual Basic) if the [IEventSubscription](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription) is no longer valid.

### Implements

[IEventSubscription.GetExecutionStrategy()](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.ieventsubscription.getexecutionstrategy)

## Remarks

If [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) or [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) are no longer valid because they were garbage collected, this method will return **Nothing**a null reference (**Nothing** in Visual Basic). Otherwise it will return a delegate that evaluates the [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) and if it returns **Truetrue** (**True** in Visual Basic) will then call [InvokeAction(Action(Of TPayload), TPayload)](https://msdn.microsoft.com/en-us/library/dn683965(v=pandp.50)). The returned delegate holds hard references to the [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) and [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) target [delegates](http://msdn2.microsoft.com/en-us/library/y22acf51). As long as the returned delegate is not garbage collected, the [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) and [Filter](https://msdn.microsoft.com/en-us/library/dn736196(v=pandp.50)) references delegates won't get collected either.

## See Also

[EventSubscription(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))

EventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)