---
TOCTitle: 'DispatcherEventSubscription(TPayload) Constructor'
Title: 'DispatcherEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.DispatcherEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,System.Threading.SynchronizationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736173(v=PandP.50)'
---


# DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Constructor

Creates a new instance of [BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

public DispatcherEventSubscription( IDelegateReference actionReference, IDelegateReference filterReference, SynchronizationContext context )Public Sub New ( actionReference As IDelegateReference, filterReference As IDelegateReference, context As SynchronizationContext )

### Parameters

actionReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference)
A reference to a delegate of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8).

filterReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference)
A reference to a delegate of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz).

context  
Type: [System.Threading.SynchronizationContext](http://msdn.microsoft.com/en-us/library/wx31754f)
The synchronization context to use for UI thread dispatching.

## Exceptions

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | When actionReference or are nullNothingnullptra null reference (Nothing in Visual Basic).                                                                                                                                                                                      |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | When the target of actionReference is not of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of filterReference is not of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz). |

## See Also

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
