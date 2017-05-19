---
TOCTitle: EventBase Methods
Title: 'EventBase Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.EventBase'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736255(v=PandP.50)'
---

Prism Class Library

EventBase Methods
=================

Include Protected Members
Include Inherited Members

The [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Contains</a></td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn2.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalpublish(system.object%5b%5d)">InternalPublish</a></td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a>.
</div></td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription)">InternalSubscribe</a></td>
<td><div class="summary">
Adds the specified <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription">IEventSubscription</a> to the subscribers' collection.
</div></td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="http://msdn2.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn2.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken)">Unsubscribe</a></td>
<td><div class="summary">
Removes the subscriber matching the <a href="https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken">SubscriptionToken</a>.
</div></td>
</tr>
</tbody>
</table>

See Also
--------

<span id="seeAlsoToggle"></span>
[EventBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
