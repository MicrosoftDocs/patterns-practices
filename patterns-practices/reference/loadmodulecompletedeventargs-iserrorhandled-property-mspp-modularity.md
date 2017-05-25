---
TOCTitle: IsErrorHandled Property
Title: 'LoadModuleCompletedEventArgs.IsErrorHandled Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.LoadModuleCompletedEventArgs.IsErrorHandled'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431277(v=PandP.50)'
---

Prism Class Library

LoadModuleCompletedEventArgs.IsErrorHandled Property
========================================================

Gets or sets a value indicating whether the error has been handled by the event subscriber.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public bool IsErrorHandled { get; set; }Public Property IsErrorHandled As Boolean Get Set
### Property Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
trueif the error is handled; otherwise, false.

Remarks
-------

 If there is an error on this event and no event subscriber sets this to true, an exception will be thrown by the event publisher.

See Also
--------


[LoadModuleCompletedEventArgs Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.loadmodulecompletedeventargs)

[LoadModuleCompletedEventArgs Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.loadmodulecompletedeventargs)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
