---
TOCTitle: GetExecutionStrategy Method
Title: 'EventSubscription(TPayload).GetExecutionStrategy Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventSubscription\`1.GetExecutionStrategy'
ms:mtpsurl: 'eventsubscription-tpayload-getexecutionstrategy-method-mspp-pubsubevents.md'
---

# EventSubscription&lt;TPayload&gt;.GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#  
public virtual Action<Object[]> GetExecutionStrategy()
```

### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)&lsqb;&rsqb;&gt;

An [Action&lt;T&gt;](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or nulla null reference (Nothing in Visual Basic) if the IEventSubscription is no longer valid.

### Implements

[IEventSubscription.GetExecutionStrategy&lpar;&rpar;](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription.getexecutionstrategy)

## Remarks

 If [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) or [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) are no longer valid because they were garbage collected, this method will return **null**a null reference (**Nothing** in Visual Basic). Otherwise it will return a delegate that evaluates the [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and if it returns **truetrue** (**True** in Visual Basic) will then call [InvokeAction(Action<TPayload>, TPayload)](/patterns-practices/reference/eventsubscription-tpayload-invokeaction-method-mspp-pubsubevents). The returned delegate holds hard references to the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) target [delegates](http://msdn2.microsoft.com/en-us/library/y22acf51). As long as the returned delegate is not garbage collected, the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) references delegates won't get collected either.

## See Also

[EventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)  
EventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  

# EventSubscription(Of TPayload).GetExecutionStrategy Method

Gets the execution strategy to publish this event.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)  
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB  
'Declaration
Public Overridable Function GetExecutionStrategy As Action(Of Object())
```

### Return Value

Type: [Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&lpar;&rpar;)

An [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) with the execution strategy, or **Nothing**a null reference (**Nothing** in Visual Basic) if the [IEventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription) is no longer valid.

### Implements

[IEventSubscription.GetExecutionStrategy()](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription.getexecutionstrategy)

## Remarks

If [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) or [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) are no longer valid because they were garbage collected, this method will return **Nothing**a null reference (**Nothing** in Visual Basic). Otherwise it will return a delegate that evaluates the [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and if it returns **Truetrue** (**True** in Visual Basic) will then call [InvokeAction(Action(Of TPayload), TPayload)](/patterns-practices/reference/eventsubscription-tpayload-invokeaction-method-mspp-pubsubevents). The returned delegate holds hard references to the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) target [delegates](http://msdn2.microsoft.com/en-us/library/y22acf51). As long as the returned delegate is not garbage collected, the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) and [Filter](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) references delegates won't get collected either.

## See Also

[EventSubscription(Of TPayload) Class](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)  
EventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)