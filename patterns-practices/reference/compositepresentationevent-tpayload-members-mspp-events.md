---
TOCTitle: 'CompositePresentationEvent(TPayload) Members'
Title: 'CompositePresentationEvent(TPayload) Members (Microsoft.Practices.Prism.Events)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1'
ms:mtpsurl: 'compositepresentationevent-tpayload-members-mspp-events.md'
---


# CompositePresentationEvent&lt;TPayload&gt; Members

The [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) type exposes the following members.

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
<td>CompositePresentationEvent&lt;TPayload&gt;
<td><div class="summary">
Initializes a new instance of the [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) class
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
<td>[Contains(Action&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-contains-method-action-tpayload-mspp-events)</td>
<td><div class="summary">
Returns <strong>truetrue</strong> (<strong>True</strong> in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).
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
<td>[Publish](/patterns-practices/reference/compositepresentationevent-tpayload-publish-method-mspp-events)</td>
<td><div class="summary">
Publishes the [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;TPayload&gt;](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-boolean-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the PublisherThread.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-mspp-events)</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-subscribe-method-action-tpayload-threadoption-boolean-predicate-tpayload-mspp-events)</td>
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
<td>[Unsubscribe(Action&lt;TPayload&gt;)](/patterns-practices/reference/compositepresentationevent-tpayload-unsubscribe-method-action-tpayload-mspp-events))</td>
<td><div class="summary">
Removes the first subscriber matching [Action&lt;T&gt;(http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.
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

[CompositePresentationEvent&lt;TPayload&gt; Class](/patterns-practices/reference/compositepresentationevent-tpayload-class-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/mspp-events-namespace)  
