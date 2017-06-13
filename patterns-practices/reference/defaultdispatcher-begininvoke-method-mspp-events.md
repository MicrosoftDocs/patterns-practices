---
TOCTitle: BeginInvoke Method
Title: 'DefaultDispatcher.BeginInvoke Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DefaultDispatcher.BeginInvoke(System.Delegate,System.Object)'
ms:mtpsurl: 'defaultdispatcher-begininvoke-method-mspp-events.md'
---

# DefaultDispatcher.BeginInvoke Method

Forwards the BeginInvoke to the current application's [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void BeginInvoke(
	Delegate method,
	Object arg
)
```

```VB
'Declaration
Public Sub BeginInvoke ( 
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

### Implements

[IDispatcherFacade.BeginInvoke(Delegate, Object)](/patterns-practices/reference/idispatcherfacade-begininvoke-method-mspp-events)

## See Also

[DefaultDispatcher Class](/patterns-practices/reference/defaultdispatcher-class-mspp-events)<br/>
[DefaultDispatcher Members](/patterns-practices/reference/defaultdispatcher-members-mspp-events)<br/>
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)<br/>