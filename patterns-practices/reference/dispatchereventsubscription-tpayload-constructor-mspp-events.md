---
TOCTitle: 'DispatcherEventSubscription(TPayload) Constructor'
Title: 'DispatcherEventSubscription(TPayload) Constructor (Microsoft.Practices.Prism.Events)'
ms:assetid: 'M:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1.\#ctor(Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.PubSubEvents.IDelegateReference,Microsoft.Practices.Prism.Events.IDispatcherFacade)'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-constructor-mspp-events.md'
---

# DispatcherEventSubscription&lt;TPayload&gt; Constructor

Creates a new instance of BackgroundEventSubscription.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public DispatcherEventSubscription(
	IDelegateReference actionReference,
	IDelegateReference filterReference,
	IDispatcherFacade dispatcher
)
```


### Parameters

*actionReference*

   Type: IDelegateReference

   A reference to a delegate of type [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz).

*filterReference*

   Type: IDelegateReference

   A reference to a delegate of type [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz).

*dispatcher*

   Type: [Microsoft.Practices.Prism.Events.IDispatcherFacade](/patterns-practices/reference/idispatcherfacade-interface-mspp-events)

   The dispatcher to use when executing the *actionReference* delegate.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>When <i>actionReference</i> or are <b>null</b>a null reference (<b>Nothing</b> in Visual Basic).
</td>
</tr>
<tr class="even">
<td>[System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)</td>
<td>When the target of <i>actionReference</i> is not of type [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of <i>filterReference</i> is not of type [Predicate&lt;T&gt;](http://msdn.microsoft.com/en-us/library/bfcke1bz).
</tr>
</tbody>
</table>

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
[DispatcherEventSubscription&lt;TPayload&gt; Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  

# DispatcherEventSubscription(Of TPayload) Constructor

Creates a new instance of BackgroundEventSubscription.

**Namespace:** [Microsoft.Practices.Prism.Events](/patterns-practices/reference/mspp-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub New ( 
	actionReference As IDelegateReference,
	filterReference As IDelegateReference,
	dispatcher As IDispatcherFacade
)
```


### Parameters

*actionReference*

   Type: IDelegateReference

   A reference to a delegate of type [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8).

*filterReference*

   Type: IDelegateReference

   A reference to a delegate of type [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz).

*dispatcher*

   Type: [Microsoft.Practices.Prism.Events.IDispatcherFacade](/patterns-practices/reference/idispatcherfacade-interface-mspp-events)

   The dispatcher to use when executing the *actionReference* delegate.

## Exceptions

<table>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[System.ArgumentNullException](http://msdn.microsoft.com/en-us/library/27426hcy)</td>
<td>When <i>actionReference</i> or are <b>Nothing</b>a null reference (<b>Nothing</b> in Visual Basic).
</td>
</tr>
<tr class="even">
<td>[System.ArgumentException](http://msdn.microsoft.com/en-us/library/3w1b3114)</td>
<td>When the target of <i>actionReference</i> is not of type [Action(Of T)](http://msdn.microsoft.com/en-us/library/018hxwa8), or the target of <i>filterReference</i> is not of type [Predicate(Of T)](http://msdn.microsoft.com/en-us/library/bfcke1bz).
</tr>
</tbody>
</table>

## See Also

[DispatcherEventSubscription(Of TPayload) Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
[DispatcherEventSubscription(Of TPayload) Members](/patterns-practices/reference/dispatchereventsubscription-tpayload-members-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)