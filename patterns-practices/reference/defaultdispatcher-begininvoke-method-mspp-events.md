---
TOCTitle: BeginInvoke Method
Title: 'DefaultDispatcher.BeginInvoke Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DefaultDispatcher.BeginInvoke(System.Delegate,System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405774(v=PandP.50)'
---


# DefaultDispatcher.BeginInvoke Method

Forwards the BeginInvoke to the current application's [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public void BeginInvoke( Delegate method, Object arg )Public Sub BeginInvoke ( method As Delegate, arg As Object )

### Parameters

method  
Type: [System.Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)
Method to be invoked.

arg  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
Arguments to pass to the invoked method.

### Implements

[IDispatcherFacade.BeginInvoke(Delegate, Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.idispatcherfacade.begininvoke(system.delegate%2csystem.object))

## See Also

[DefaultDispatcher Class](https://msdn.microsoft.com/library/microsoft.practices.prism.events.defaultdispatcher)

[DefaultDispatcher Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.defaultdispatcher)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
