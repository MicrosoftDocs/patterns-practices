---
TOCTitle: 'DispatcherEventSubscription(TPayload) Class'
Title: 'DispatcherEventSubscription(TPayload) Class (Microsoft.Practices.Prism.Events)'
ms:assetid: 'T:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-class-mspp-events.md'
---


# DispatcherEventSubscription&lt;TPayload&gt; Class

Extends EventSubscription to invoke the Action delegate in a specific [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
[ObsoleteAttribute]
public class DispatcherEventSubscription<TPayload> : EventSubscription<TPayload>
```

## Type Parameters


TPayload  
The type to use for the generic [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  EventSubscription&lt;TPayload&gt;  
    Microsoft.Practices.Prism.Events.DispatcherEventSubscription&lt;TPayload&gt;

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)

[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)

----------------------------

# DispatcherEventSubscription(Of TPayload) Class

Extends EventSubscription to invoke the Action delegate in a specific [Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907).

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
<ObsoleteAttribute> 
Public Class DispatcherEventSubscription(Of TPayload)
	Inherits EventSubscription(Of TPayload)
```
## Type Parameters


TPayload  
The type to use for the generic [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8) and [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz) types.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
  EventSubscription(Of TPayload)  
    Microsoft.Practices.Prism.Events.DispatcherEventSubscription(Of TPayload)

## See Also

[DispatcherEventSubscription(Of TPayload) Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)

[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)
