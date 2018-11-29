---
TOCTitle: 'DispatcherEventSubscription(TPayload) Members'
Title: 'DispatcherEventSubscription(TPayload) Members (Microsoft.Practices.Prism.Events)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1'
ms:mtpsurl: 'dispatchereventsubscription-tpayload-members-mspp-events.md'
---

# DispatcherEventSubscription&lt;TPayload&gt; Members

The [ DispatcherEventSubscription&lt;TPayload&gt;](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events) type exposes the following members.

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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>DispatcherEventSubscription&lt;TPayload&gt;</td>
<td><div class="summary">
Creates a new instance of BackgroundEventSubscription.
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
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47" data-raw-source="[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7" data-raw-source="[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td>GetExecutionStrategy</td>
<td>(Inherited from EventSubscription&lt;<a href="/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events" data-raw-source="[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)">TPayload</a>&gt;.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y" data-raw-source="[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9" data-raw-source="[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65" data-raw-source="[Type](http://msdn.microsoft.com/en-us/library/42892f65)">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="/patterns-practices/reference/dispatchereventsubscription-tpayload-invokeaction-method-mspp-events" data-raw-source="[InvokeAction](/patterns-practices/reference/dispatchereventsubscription-tpayload-invokeaction-method-mspp-events)">InvokeAction</a></td>
<td><div class="summary">
Invokes the specified <a href="http://msdn.microsoft.com/en-us/library/018hxwa8" data-raw-source="[Action&amp;lt;T&amp;gt;](http://msdn.microsoft.com/en-us/library/018hxwa8)">Action&lt;T&gt;</a> asynchronously in the specified <a href="http://msdn.microsoft.com/en-us/library/ms615907" data-raw-source="[Dispatcher](http://msdn.microsoft.com/en-us/library/ms615907)">Dispatcher</a>.
</div>
(Overrides EventSubscriptionInvokeAction(Action&lt;UTP&gt;, UTP).)</td>
</tr>
<tr class="odd">
<td><img src="/patterns-practices/reference/images/protmethod.gif" alt="Protected method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a" data-raw-source="[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="/patterns-practices/reference/images/public-method.gif" alt="Public method"/></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2" data-raw-source="[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b" data-raw-source="[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)">Object</a>.)</td>
</tr>
</tbody>
</table>

## Properties


|                                                                                                  | Name              | Description                                                                                                                                                         |
|--------------------------------------------------------------------------------------------------|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Public property](/patterns-practices/reference/images/pubproperty.gif) | Action            | (Inherited from EventSubscription&lt;[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)&gt;. |
| ![Public property](/patterns-practices/reference/images/pubproperty.gif) | Filter            | (Inherited from EventSubscription&lt;[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)&gt;|
| ![Public property](/patterns-practices/reference/images/pubproperty.gif) | SubscriptionToken | (Inherited from EventSubscription&lt;[TPayload](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)&gt;|

## See Also

[DispatcherEventSubscription&lt;TPayload&gt; Class](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
[Microsoft.Practices.Prism.Events Namespace](/patterns-practices/reference/dispatchereventsubscription-tpayload-class-mspp-events)  
