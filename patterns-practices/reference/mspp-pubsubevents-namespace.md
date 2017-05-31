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
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents">BackgroundEventSubscription&lt;TPayload&gt;</a></td>
<td><div class="summary">
Extends <a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents">EventSubscription&lt;TPayload&gt;</a> to invoke the <a href="/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents">Action</a> delegate in a background thread.

<td>[BackgroundEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/backgroundeventsubscription-tpayload-class-mspp-pubsubevents)</td>
<td><div class="summary">
Extends [EventSubscription&lt;TPayload&gt;](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents) to invoke the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) delegate in a background thread.

</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/dataeventargs-tdata-class-mspp-pubsubevents">DataEventArgs&lt;TData&gt;</a></td>

<td>[DataEventArgs&lt;TData&gt;](/patterns-practices/reference/dataeventargs-tdata-class-mspp-pubsubevents)</td>

<td><div class="summary">
Generic arguments class to pass to event handlers that need to receive data.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/delegatereference-class-mspp-pubsubevents">DelegateReference</a></td>

<td>[DelegateReference](/patterns-practices/reference/delegatereference-class-mspp-pubsubevents)</td>

<td><div class="summary">
Represents a reference to a [Delegate](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/y22acf51) that may contain a [WeakReference](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target. This class is used internally by the Prism Library.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents">DispatcherEventSubscription&lt;TPayload&gt;</a></td>
<td><div class="summary">
Extends <a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents">EventSubscription&lt;TPayload&gt;</a> to invoke the <a href="/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents">Action</a> delegate in a specific <a href="http://msdn.microsoft.com/en-us/library/wx31754f">SynchronizationContext</a>.

<td>[DispatcherEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-pubsubevents)</td>
<td><div class="summary">
Extends [EventSubscription&lt;TPayload&gt;](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents) to invoke the [Action](/patterns-practices/reference/eventsubscription-tpayload-action-property-mspp-pubsubevents) delegate in a specific [SynchronizationContext](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/wx31754f).

</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents">EventAggregator</a></td>
<td><div class="summary">
Implements <a href="/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents">IEventAggregator</a>.

<td>[EventAggregator](/patterns-practices/reference/eventaggregator-class-mspp-pubsubevents)</td>
<td><div class="summary">
Implements [IEventAggregator](/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents).

</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents">EventBase</a></td>

<td>[EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)</td>

<td><div class="summary">
Defines a base class to publish and subscribe to events.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents">EventSubscription&lt;TPayload&gt;</a></td>

<td>[EventSubscription&lt;TPayload&gt;](/patterns-practices/reference/eventsubscription-tpayload-class-mspp-pubsubevents)</td>

<td><div class="summary">
Provides a way to retrieve a [Delegate](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/y22acf51) to execute an action depending on the value of a second filter predicate that returns true if the action should execute.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents">PubSubEvent&lt;TPayload&gt;</a></td>

<td>[PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)</td>

<td><div class="summary">
Defines a class that manages publication and subscription to events.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>

<td><a href="/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents">SubscriptionToken</a></td>
<td><div class="summary">
Subscription token returned from <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents">EventBase</a> on subscribe.

<td>[SubscriptionToken](/patterns-practices/reference/subscriptiontoken-class-mspp-pubsubevents)</td>
<td><div class="summary">
Subscription token returned from [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents) on subscribe.

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
<td>![Public interface](/images/public-interface.gif)</td>

<td><a href="/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents">IDelegateReference</a></td>

<td>[IDelegateReference](/patterns-practices/reference/idelegatereference-interface-mspp-pubsubevents)</td>

<td><div class="summary">
Represents a reference to a [Delegate](/patterns-practices/reference/http://msdn.microsoft.com/en-us/library/y22acf51).
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/images/public-interface.gif)</td>

<td><a href="/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents">IEventAggregator</a></td>

<td>[IEventAggregator](/patterns-practices/reference/ieventaggregator-interface-mspp-pubsubevents)</td>

<td><div class="summary">
Defines an interface to get instances of an event type.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/images/public-interface.gif)</td>

<td><a href="/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents">IEventSubscription</a></td>
<td><div class="summary">
Defines a contract for an event subscription to be used by <a href="/patterns-practices/reference/eventbase-class-mspp-pubsubevents">EventBase</a>.

<td>[IEventSubscription](/patterns-practices/reference/ieventsubscription-interface-mspp-pubsubevents)</td>
<td><div class="summary">
Defines a contract for an event subscription to be used by [EventBase](/patterns-practices/reference/eventbase-class-mspp-pubsubevents).

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
<td>![Public enumeration](/images/pubenumeration.gif)</td>

<td><a href="/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents">ThreadOption</a></td>
<td><div class="summary">
Specifies on which thread a <a href="/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents">PubSubEvent&lt;TPayload&gt;</a> subscriber will be called.

<td>[ThreadOption](/patterns-practices/reference/threadoption-enumeration-mspp-pubsubevents)</td>
<td><div class="summary">
Specifies on which thread a [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) subscriber will be called.

</div></td>
</tr>
</tbody>
</table>
