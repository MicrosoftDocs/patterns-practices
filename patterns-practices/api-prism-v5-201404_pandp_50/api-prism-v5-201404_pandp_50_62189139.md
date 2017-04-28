---
TOCTitle: 'CompositePresentationEvent(TPayload) Methods'
Title: 'CompositePresentationEvent(TPayload) Methods (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430980(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Methods
=================================================================

Include Protected Members
Include Inherited Members

The [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
Contains(SubscriptionToken)
(Inherited from EventBase.)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Contains(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.contains(system.action%7b%600%7d))
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif "Protected method")
InternalPublish
(Inherited from EventBase.)
![](https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif "Protected method")
InternalSubscribe
(Inherited from EventBase.)
![](https://msdn.microsoft.com/en-us/Gg430980.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Publish](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.publish(%600))
Publishes the [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601).

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d))
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption))
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean))
Subscribes a delegate to an event that will be published on the PublisherThread.

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
Unsubscribe(SubscriptionToken)
(Inherited from EventBase.)
![](https://msdn.microsoft.com/en-us/Gg430980.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.unsubscribe(system.action%7b%600%7d))
Removes the first subscriber matching [Action&lt;(Of &lt;(T&gt;)&gt;)](http://msdn2.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
