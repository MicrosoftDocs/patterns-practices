---
TOCTitle: 'BackgroundEventSubscription(TPayload) Class'
Title: 'BackgroundEventSubscription(TPayload) Class (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'T:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683933(v=PandP.50)'
---

# BackgroundEventSubscription(Of TPayload) Class

Extends [EventSubscription(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50)) to invoke the [Action](https://msdn.microsoft.com/en-us/library/dn736296(v=pandp.50)) delegate in a background thread.

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```C#
    public class BackgroundEventSubscription<TPayload> : EventSubscription<TPayload>
```
```VB
    'Declaration
    Public Class BackgroundEventSubscription(Of TPayload)
	   Inherits EventSubscription(Of TPayload)
```

## Type Parameters

<span id="templatesToggle"></span>
*TPayload*  
    The type to use for the generic [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  
  [Microsoft.Practices.Prism.PubSubEvents.EventSubscription](https://msdn.microsoft.com/en-us/library/dn683956(v=pandp.50))(Of TPayload)
    Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription(Of TPayload)

## See Also

BackgroundEventSubscription(Of TPayload) Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
