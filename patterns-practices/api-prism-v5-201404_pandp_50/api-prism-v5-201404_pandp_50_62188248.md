---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683938(v=PandP.50)'
---

Prism Class Library

PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Methods
==================================================

Include Protected Members
Include Inherited Members

The [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Contains(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.contains(system.action%7b%600%7d))
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Contains(SubscriptionToken)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken))
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken).

(Inherited from [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[InternalPublish](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalpublish(system.object%5b%5d))
Calls all the execution strategies exposed by the list of [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription).

(Inherited from [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase).)
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[InternalSubscribe](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription))
Adds the specified [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription) to the subscribers' collection.

(Inherited from [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase).)
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Publish](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.publish(%600))
Publishes the [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d))
Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption). [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption))
Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean))
Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.threadoption).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.pubsubevent%601.unsubscribe(system.action%7b%600%7d))
Removes the first subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe(SubscriptionToken)](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken))
Removes the subscriber matching the [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken).

(Inherited from [EventBase](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase).)

See Also
--------

<span id="seeAlsoToggle"></span>
[PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.pubsubevent%601)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
