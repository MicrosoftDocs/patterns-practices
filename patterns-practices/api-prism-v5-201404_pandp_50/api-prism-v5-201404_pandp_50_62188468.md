---
TOCTitle: 'Microsoft.Practices.Prism.PubSubEvents Namespace'
Title: 'Microsoft.Practices.Prism.PubSubEvents Namespace ()'
ms:assetid: 'N:Microsoft.Practices.Prism.PubSubEvents'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683966(v=PandP.50)'
---

Prism Class Library

Microsoft.Practices.Prism.PubSubEvents Namespace
================================================

 

Classes
-------

<span id="classToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.backgroundeventsubscription%601">BackgroundEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a></td>
<td><div class="summary">
Extends <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601">EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a> to invoke the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action">Action</a> delegate in a background thread.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dataeventargs%601">DataEventArgs&lt;(Of &lt;(TData&gt;)&gt;)</a></td>
<td><div class="summary">
Generic arguments class to pass to event handlers that need to receive data.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.delegatereference">DelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn2.microsoft.com/en-us/library/y22acf51">Delegate</a> that may contain a <a href="http://msdn2.microsoft.com/en-us/library/hbh8w2zd">WeakReference</a> to the target. This class is used internally by the Prism Library.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.dispatchereventsubscription%601">DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a></td>
<td><div class="summary">
Extends <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601">EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a> to invoke the <a href="https://msdn.microsoft.com/p:microsoft.practices.prism.pubsubevents.eventsubscription%601.action">Action</a> delegate in a specific <a href="http://msdn2.microsoft.com/en-us/library/wx31754f">SynchronizationContext</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventaggregator">EventAggregator</a></td>
<td><div class="summary">
Implements <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventaggregator">IEventAggregator</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a></td>
<td><div class="summary">
Defines a base class to publish and subscribe to events.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventsubscription%601">EventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a></td>
<td><div class="summary">
Provides a way to retrieve a <a href="http://msdn2.microsoft.com/en-us/library/y22acf51">Delegate</a> to execute an action depending on the value of a second filter predicate that returns true if the action should execute.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601">PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a></td>
<td><div class="summary">
Defines a class that manages publication and subscription to events.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubclass(en-us,PandP.50).gif" title="Public class" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a></td>
<td><div class="summary">
Subscription token returned from <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a> on subscribe.
</div></td>
</tr>
</tbody>
</table>

Interfaces
----------

<span id="interfaceToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Interface</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.idelegatereference">IDelegateReference</a></td>
<td><div class="summary">
Represents a reference to a <a href="http://msdn2.microsoft.com/en-us/library/y22acf51">Delegate</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventaggregator">IEventAggregator</a></td>
<td><div class="summary">
Defines an interface to get instances of an event type.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubinterface(en-us,PandP.50).gif" title="Public interface" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a></td>
<td><div class="summary">
Defines a contract for an event subscription to be used by <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase">EventBase</a>.
</div></td>
</tr>
</tbody>
</table>

Enumerations
------------

<span id="enumerationToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Enumeration</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn683966.pubenumeration(en-us,PandP.50).gif" title="Public enumeration" /></td>
<td><a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption">ThreadOption</a></td>
<td><div class="summary">
Specifies on which thread a <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601">PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)</a> subscriber will be called.
</div></td>
</tr>
</tbody>
</table>
