---
TOCTitle: 'Microsoft.Practices.Prism.PubSubEvents Namespace'
Title: 'Microsoft.Practices.Prism.PubSubEvents Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.PubSubEvents'
ms:mtpsurl: 'mspp-pubsubevents-namespace.md'
---


# Microsoft.Practices.Prism.PubSubEvents Namespace

 
## Classes

<span id="classToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="backgroundeventsubscription-tpayload-class-mspp-pubsubevents.md" data-raw-source="[BackgroundEventSubscription(of TPayload)](backgroundeventsubscription-tpayload-class-mspp-pubsubevents.md)">BackgroundEventSubscription(of TPayload)</a></td>
<td><div class="summary">
Extends <a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents" data-raw-source="[EventSubscription(of TPayload)](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)">EventSubscription(of TPayload)</a> to invoke the <a href="/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents" data-raw-source="[Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents)">Action</a> delegate in a background thread.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/dataeventargs-tdata-class-mspp-pubsubevents" data-raw-source="[DataEventArgs(of TData)](/patterns-practices/reference/dataeventargs-tdata-class-mspp-pubsubevents)">DataEventArgs(of TData)</a></td>
<td><div class="summary">
Generic arguments class to pass to event handlers that need to receive data.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/delegatereference-class-mspp-pubsubevents" data-raw-source="[DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents)">DelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn.microsoft.com/en-us/library/y22acf51" data-raw-source="[Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)">Delegate</a> that may contain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd" data-raw-source="[WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd)">WeakReference</a> to the target. This class is used internally by the Prism Library.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents" data-raw-source="[DispatcherEventSubscription(of TPayload)](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)">DispatcherEventSubscription(of TPayload)</a></td>
<td><div class="summary">
Extends <a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents" data-raw-source="[EventSubscription(of TPayload)](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)">EventSubscription(of TPayload)</a> to invoke the <a href="/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents" data-raw-source="[Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents)">Action</a> delegate in a specific <a href="http://msdn.microsoft.com/en-us/library/wx31754f" data-raw-source="[SynchronizationContext](http://msdn.microsoft.com/en-us/library/wx31754f)">SynchronizationContext</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents" data-raw-source="[EventAggregator](/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents)">EventAggregator</a></td>
<td><div class="summary">
Implements <a href="/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents" data-raw-source="[IEventAggregator](/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents)">IEventAggregator</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a></td>
<td><div class="summary">
Defines a base class to publish and subscribe to events.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents" data-raw-source="[EventSubscription(of TPayload)](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)">EventSubscription(of TPayload)</a></td>
<td><div class="summary">
Provides a way to retrieve a <a href="http://msdn.microsoft.com/en-us/library/y22acf51" data-raw-source="[Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)">Delegate</a> to execute an action depending on the value of a second filter predicate that returns true if the action should execute.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents" data-raw-source="[PubSubEvent(of TPayload)](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)">PubSubEvent(of TPayload)</a></td>
<td><div class="summary">
Defines a class that manages publication and subscription to events.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-class.gif" alt="Public class"/></td>
<td><a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents" data-raw-source="[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)">SubscriptionToken</a></td>
<td><div class="summary">
Subscription token returned from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a> on subscribe.
</div></td>
</tr>
</tbody>
</table>

## Interfaces

<span id="interfaceToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents" data-raw-source="[IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)">IDelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn.microsoft.com/en-us/library/y22acf51" data-raw-source="[Delegate](http://msdn.microsoft.com/en-us/library/y22acf51)">Delegate</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents" data-raw-source="[IEventAggregator](/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents)">IEventAggregator</a></td>
<td><div class="summary">
Defines an interface to get instances of an event type.
</div></td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-interface.gif" alt="Public interface"/></td>
<td><a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents" data-raw-source="[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)">IEventSubscription</a></td>
<td><div class="summary">
Defines a contract for an event subscription to be used by <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents" data-raw-source="[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)">EventBase</a>.
</div></td>
</tr>
</tbody>
</table>

## Enumerations

<span id="enumerationToggle"></span>
<table>

<thead>
<tr class="header">
<th> </th>
<th>Enumeration</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/pubenumeration.gif" alt="Public enumeration"/></td>
<td><a href="/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents" data-raw-source="[ThreadOption](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)">ThreadOption</a></td>
<td><div class="summary">
Specifies on which thread a <a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents" data-raw-source="[PubSubEvent(of TPayload)](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)">PubSubEvent(of TPayload)</a> subscriber will be called.
</div></td>
</tr>
</tbody>
</table>