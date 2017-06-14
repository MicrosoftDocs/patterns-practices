---
TOCTitle: 'CompositePresentationEvent(TPayload) Members'
Title: 'CompositePresentationEvent(TPayload) Members (Microsoft.Practices.Prism.Events)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1'
ms:mtpsurl: 'compositepresentationevent-tpayload-members-mspp-events.md'
---

# CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members

The [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601) type exposes the following members.

## Constructors


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.)</td>
<td><div class="summary">
Initializes a new instance of the [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601) class
</div></td>
</tr>
</tbody>
</table>

## Methods


<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>Contains(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Contains(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.contains(system.action%7b%600%7d))</td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>InternalPublish</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>InternalSubscribe</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Publish](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.publish(%600))</td>
<td><div class="summary">
Publishes the [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d))</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption))</td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean))</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>Unsubscribe(SubscriptionToken)</td>
<td>(Inherited from EventBase.)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Unsubscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601.unsubscribe(system.action%7b%600%7d))</td>
<td><div class="summary">
Removes the first subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.
</div></td>
</tr>
</tbody>
</table>

## Properties


|                                                                                                      | Name                   | Description                 |
|------------------------------------------------------------------------------------------------------|------------------------|-----------------------------|
| ![Protected property](/patterns-practices/reference/images/protproperty.gif) | Subscriptions          | (Inherited from EventBase.) |
| ![Public property](/patterns-practices/reference/images/pubproperty.gif)     | SynchronizationContext | (Inherited from EventBase.) |

## See Also
[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.events.compositepresentationevent%601)  
[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.events)  