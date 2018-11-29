---
TOCTitle: InternalPublish Method
Title: 'EventBase.InternalPublish Method (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.EventBase.InternalPublish(System.Object[])'
ms:mtpsurl: 'eventbase-internalpublish-method-mspp-pubsubevents.md'
---


# EventBase.InternalPublish Method

Calls all the execution strategies exposed by the list of [IEventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-mvvm-namespace)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)  
**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    pprotected virtual void InternalPublish(
			params Object[] arguments
    )
``` 
### Parameters

*arguments*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)[]  
The arguments that will be passed to the listeners.

## Remarks

Before executing the strategies, this class will prune all the subscribers from the list that return a **null**a null reference (**Nothing** in Visual Basic)[Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) when calling the [GetExecutionStrategy()](/patterns-practices/reference/ieventsubscription-getexecutionstrategy-method-mspp-pubsubevents) method.

## Syntax

```VB
    'Declaration
    Protected Overridable Sub InternalPublish ( 
			ParamArray arguments As Object()
	)
``` 
### Parameters

*arguments*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)()  
The arguments that will be passed to the listeners.

## Remarks

Before executing the strategies, this class will prune all the subscribers from the list that return a **Nothing**a null reference (**Nothing** in Visual Basic)[Action(Of T) ](http://msdn.microsoft.com/en-us/library/018hxwa8) when calling the [GetExecutionStrategy](/patterns-practices/reference/ieventsubscription-getexecutionstrategy-method-mspp-pubsubevents) method.
## See Also

[EventBase Class](/patterns-practices/reference/mspp-mvvm-namespace.eventbase)  
EventBase Members  
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-mvvm-namespace)  