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
<td><a href="backgroundeventsubscription-tpayload-class-mspp-pubsubevents.md">BackgroundEventSubscription&lt;TPayload&gt;</a></td>
<td><div class="summary">
Extends <a href="eventsubscription-tpayload-class-mspp-pubsubevents.md">EventSubscription&lt;TPayload&gt;</a> to invoke the <a href="eventsubscription-tpayload-action-property-mspp-pubsubevents.md">Action</a> delegate in a background thread.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="dataeventargs-tdata-class-mspp-pubsubevents.md">DataEventArgs&lt;TData&gt;</a></td>
<td><div class="summary">
Generic arguments class to pass to event handlers that need to receive data.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="delegatereference-class-mspp-pubsubevents.md">DelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn.microsoft.com/en-us/library/y22acf51">Delegate</a> that may contain a <a href="http://msdn.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target. This class is used internally by the Prism Library.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="dispatchereventsubscription-tpayload-class-mspp-pubsubevents.md">DispatcherEventSubscription&lt;TPayload&gt;</a></td>
<td><div class="summary">
Extends <a href="eventsubscription-tpayload-class-mspp-pubsubevents.md">EventSubscription&lt;TPayload&gt;</a> to invoke the <a href="eventsubscription-tpayload-action-property-mspp-pubsubevents.md">Action</a> delegate in a specific <a href="http://msdn.microsoft.com/en-us/library/wx31754f">SynchronizationContext</a>.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="eventaggregator-class-mspp-pubsubevents.md">EventAggregator</a></td>
<td><div class="summary">
Implements <a href="ieventaggregator-interface-mspp-pubsubevents.md">IEventAggregator</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="eventbase-class-mspp-pubsubevents.md">EventBase</a></td>
<td><div class="summary">
Defines a base class to publish and subscribe to events.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="eventsubscription-tpayload-class-mspp-pubsubevents.md">EventSubscription&lt;TPayload&gt;</a></td>
<td><div class="summary">
Provides a way to retrieve a <a href="http://msdn.microsoft.com/en-us/library/y22acf51">Delegate</a> to execute an action depending on the value of a second filter predicate that returns true if the action should execute.
</div></td>
</tr>
<tr class="even">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="pubsubevent-tpayload-class-mspp-pubsubevents.md">PubSubEvent&lt;TPayload&gt;</a></td>
<td><div class="summary">
Defines a class that manages publication and subscription to events.
</div></td>
</tr>
<tr class="odd">
<td>![Public class](/images/public-class.gif)</td>
<td><a href="subscriptiontoken-class-mspp-pubsubevents.md">SubscriptionToken</a></td>
<td><div class="summary">
Subscription token returned from <a href="eventbase-class-mspp-pubsubevents.md">EventBase</a> on subscribe.
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
<td><a href="idelegatereference-interface-mspp-pubsubevents.md">IDelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn.microsoft.com/en-us/library/y22acf51">Delegate</a>.
</div></td>
</tr>
<tr class="even">
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="ieventaggregator-interface-mspp-pubsubevents.md">IEventAggregator</a></td>
<td><div class="summary">
Defines an interface to get instances of an event type.
</div></td>
</tr>
<tr class="odd">
<td>![Public interface](/images/public-interface.gif)</td>
<td><a href="ieventsubscription-interface-mspp-pubsubevents.md">IEventSubscription</a></td>
<td><div class="summary">
Defines a contract for an event subscription to be used by <a href="eventbase-class-mspp-pubsubevents.md">EventBase</a>.
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
<td><a href="threadoption-enumeration-mspp-pubsubevents.md">ThreadOption</a></td>
<td><div class="summary">
Specifies on which thread a <a href="pubsubevent-tpayload-class-mspp-pubsubevents.md">PubSubEvent&lt;TPayload&gt;</a> subscriber will be called.
</div></td>
</tr>
</tbody>
</table>
