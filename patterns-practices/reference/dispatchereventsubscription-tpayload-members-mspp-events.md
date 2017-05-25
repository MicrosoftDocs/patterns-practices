---
TOCTitle: 'DispatcherEventSubscription(TPayload) Members'
Title: 'DispatcherEventSubscription(TPayload) Members (Microsoft.Practices.Prism.Events)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Events.DispatcherEventSubscription\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430769(v=PandP.50)'
---


# DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Members

The [DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601) type exposes the following members.

## Constructors

<span id="constructorTableToggle"></span>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601.">DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;)</a></td>
<td><div class="summary">
Creates a new instance of BackgroundEventSubscription.
</div></td>
</tr>
</tbody>
</table>

## Methods

<span id="methodTableToggle"></span>
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
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/bsc2ak47">Equals</a></td>
<td><div class="summary">
Determines whether the specified <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a> is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="https://msdn.microsoft.com/en-us/Gg430769.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/4k87zsw7">Finalize</a></td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td>GetExecutionStrategy</td>
<td>(Inherited from EventSubscription&lt;(Of &lt;(<a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601">TPayload</a>&gt;)&gt;).)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/zdee4b3y">GetHashCode</a></td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/dfwy45w9">GetType</a></td>
<td><div class="summary">
Gets the <a href="http://msdn.microsoft.com/en-us/library/42892f65">Type</a> of the current instance.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601.invokeaction(system.action%7b%600%7d%2c%600)">InvokeAction</a></td>
<td><div class="summary">
Invokes the specified <a href="http://msdn.microsoft.com/en-us/library/018hxwa8">Action&lt;(Of &lt;(T&gt;)&gt;)</a> asynchronously in the specified <a href="http://msdn.microsoft.com/en-us/library/ms615907">Dispatcher</a>.
</div>
(Overrides EventSubscriptionInvokeAction(Action&lt;(Of &lt;(UTP&gt;)&gt;), UTP).)</td>
</tr>
<tr class="odd">
<td><img src="https://msdn.microsoft.com/en-us/Gg430769.protmethod(en-us,PandP.50).gif" title="Protected method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/57ctke0a">MemberwiseClone</a></td>
<td><div class="summary">
Creates a shallow copy of the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/public-method.gif" title="Public method" /></td>
<td><a href="http://msdn.microsoft.com/en-us/library/7bxwbwt2">ToString</a></td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b">Object</a>.)</td>
</tr>
</tbody>
</table>

## Properties

<span id="propertyTableToggle"></span>
|                                                                                                  | Name              | Description                                                                                                                                                         |
|--------------------------------------------------------------------------------------------------|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![](https://msdn.microsoft.com/en-us/Gg430769.pubproperty(en-us,PandP.50).gif "Public property") | Action            | (Inherited from EventSubscription&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)&gt;)&gt;).) |
| ![](https://msdn.microsoft.com/en-us/Gg430769.pubproperty(en-us,PandP.50).gif "Public property") | Filter            | (Inherited from EventSubscription&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)&gt;)&gt;).) |
| ![](https://msdn.microsoft.com/en-us/Gg430769.pubproperty(en-us,PandP.50).gif "Public property") | SubscriptionToken | (Inherited from EventSubscription&lt;(Of &lt;([TPayload](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)&gt;)&gt;).) |

## See Also

[DispatcherEventSubscription&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/library/microsoft.practices.prism.events.dispatchereventsubscription%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.events)
