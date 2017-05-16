---
TOCTitle: 'DispatcherEventSubscription(TPayload) Constructor'
Title: 'DispatcherEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.Events.IDispatcherFacade)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683971(v=PandP.50)'
---

Prism Class Library

DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Constructor
======================================================================

Creates a new instance of BackgroundEventSubscription.

**Namespace:** [Microsoft.Practices.Prism.Events](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public DispatcherEventSubscription( IDelegateReference actionReference, IDelegateReference filterReference, IDispatcherFacade dispatcher )Public Sub New ( actionReference As IDelegateReference, filterReference As IDelegateReference, dispatcher As IDispatcherFacade )
#### Parameters

actionReference  
Type: IDelegateReference
A reference to a delegate of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

<!-- -->

filterReference  
Type: IDelegateReference
A reference to a delegate of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz).

<!-- -->

dispatcher  
Type: [Microsoft.Practices.Prism.Events..::.IDispatcherFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.events.idispatcherfacade)
The dispatcher to use when executing the actionReference delegate.

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System..::.ArgumentNullException](http://msdn2.microsoft.com/en-us/library/27426hcy) | When actionReference or are nullNothingnullptra null reference (Nothing in Visual Basic).                                                                                                                                                                                      |
| [System..::.ArgumentException](http://msdn2.microsoft.com/en-us/library/3w1b3114)     | When the target of actionReference is not of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8), or the target of filterReference is not of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/bfcke1bz). |

See Also
--------

<span id="seeAlsoToggle"></span>
[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.dispatchereventsubscription%601)

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
