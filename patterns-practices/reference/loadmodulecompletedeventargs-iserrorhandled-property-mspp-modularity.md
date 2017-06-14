---
TOCTitle: IsErrorHandled Property
Title: 'LoadModuleCompletedEventArgs.IsErrorHandled Property (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'P:Microsoft.Practices.Prism.Modularity.LoadModuleCompletedEventArgs.IsErrorHandled'
ms:mtpsurl: 'loadmodulecompletedeventargs-iserrorhandled-property-mspp-modularity.md'
---


# LoadModuleCompletedEventArgs.IsErrorHandled Property

Gets or sets a value indicating whether the error has been handled by the event subscriber.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool IsErrorHandled { get; set; }
```
```VB
'Declaration
Public Property IsErrorHandled As Boolean
	Get
	Set
```

### Property Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
trueif the error is handled; otherwise, false.

## Remarks

 If there is an error on this event and no event subscriber sets this to true, an exception will be thrown by the event publisher.

## See Also

[LoadModuleCompletedEventArgs Class](/patterns-practices/reference/loadmodulecompletedeventargs-class-mspp-mefextensions-modularity)  
[LoadModuleCompletedEventArgs Members](/patterns-practices/reference/loadmodulecompletedeventargs-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-regions-namespace)  