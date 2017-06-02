---
TOCTitle: 'BackgroundEventSubscription(TPayload) Constructor'
Title: 'BackgroundEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'M:Microsoft.Practices.Prism.PubSubEvents.BackgroundEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference)'
ms:mtpsurl: 'backgroundeventsubscription-tpayload-constructor-mspp-pubsubevents.md'
---

# BackgroundEventSubscription&lt;TPayload&gt; Constructor 

Creates a new instance of [BackgroundEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll)

**Version:** 1.0.0.0 (1.0.0.0)

## Syntax

```C#
public BackgroundEventSubscription(
	IDelegateReference actionReference,
	IDelegateReference filterReference
)
```

### Parameters

*actionReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)

A reference to a delegate of type [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).

*filterReference*  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)

A reference to a delegate of type [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz).

## Exceptions

| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | When *actionReference* or are **null**a null reference (**Nothing** in Visual Basic).                                                                                                                                                                                     |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | When the target of *actionReference* is not of type [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of *filterReference* is not of type [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz). |

## See Also

[BackgroundEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)

BackgroundEventSubscription&lt;TPayload&gt; Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)

# BackgroundEventSubscription(Of TPayload) Constructor

Creates a new instance of [BackgroundEventSubscription(Of TPayload) ](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents).

**Namespace:** [Microsoft.Practices.Prism.PubSubEvents](/patterns-practices/reference/mspp-pubsubevents-namespace)

**Assembly:** Microsoft.Practices.Prism.PubSubEvents (in Microsoft.Practices.Prism.PubSubEvents.dll) Version: 1.0.0.0 (1.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	actionReference As IDelegateReference,
	filterReference As IDelegateReference
)
```

### Parameters

*actionReference*

Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)

A reference to a delegate of type [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8).

*filterReference*  
Type: [Microsoft.Practices.Prism.PubSubEvents.IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)

A reference to a delegate of type [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz).

## Exceptions

| Exception                                                                             | Condition                                                                                                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy) | When *actionReference* or are **Nothing**a null reference (**Nothing** in Visual Basic).                                                                                                                                                                                     |
| [System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)     | When the target of *actionReference* is not of type [ Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of *filterReference* is not of type [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz). |

## See Also

[BackgroundEventSubscription(Of TPayload)  Class](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)

BackgroundEventSubscription(Of TPayload)  Members

[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)