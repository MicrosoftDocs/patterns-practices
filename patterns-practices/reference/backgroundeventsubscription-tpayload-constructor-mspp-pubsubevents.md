---
TOCTitle: 'BackgroundEventSubscription(TPayload) Constructor'
Title: 'BackgroundEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference)'
ms:mtpsurl: 'backgroundeventsubscription-tpayload-constructor-mspp-pubsubevents.md'
---

Prism Class Library

BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Constructor
======================================================================

Creates a new instance of [BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax


public BackgroundEventSubscription( IDelegateReference actionReference, IDelegateReference filterReference )Public Sub New ( actionReference As IDelegateReference, filterReference As IDelegateReference )

### Parameters

actionReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference)
A reference to a delegate of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8).

filterReference  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.idelegatereference)
A reference to a delegate of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz).

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | When actionReference or are nullNothingnullptra null reference (Nothing in Visual Basic).                                                                                                                                                                                      |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | When the target of actionReference is not of type [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of filterReference is not of type [Predicate&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/bfcke1bz). |

See Also
--------


[BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)

[BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents)
