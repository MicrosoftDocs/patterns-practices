---
TOCTitle: BeginInvoke Method
Title: 'IDispatcherFacade.BeginInvoke Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.IDispatcherFacade.BeginInvoke(System.Delegate,System.Object)'
ms:mtpsurl: 'idispatcherfacade-begininvoke-method-mspp-events.md'
---

# IDispatcherFacade.BeginInvoke Method

Dispatches an invocation to the method received as parameter.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
void BeginInvoke(
	Delegate method,
	Object arg
)
```

```VB
'Declaration
Sub BeginInvoke ( 
	method As Delegate,
	arg As Object
)
```

### Parameters

*method*  
Type: [System.Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)  
Method to be invoked.

*arg*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
Arguments to pass to the invoked method.

## See Also

[IDispatcherFacade Interface](/patterns-practices/reference/idispatcherfacade-interface-mspp-events)<br/>
[IDispatcherFacade Members](/patterns-practices/reference/idispatcherfacade-members-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>