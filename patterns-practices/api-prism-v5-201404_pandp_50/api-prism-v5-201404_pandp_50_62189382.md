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
 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[Contains](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken))
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken).

![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif "Protected method")
[InternalPublish](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalpublish(system.object%5b%5d))
Calls all the execution strategies exposed by the list of [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription).

![](https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif "Protected method")
[InternalSubscribe](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription))
Adds the specified [IEventSubscription](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.ieventsubscription) to the subscribers' collection.

![](https://msdn.microsoft.com/en-us/Dn736255.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn736255.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe](https://msdn.microsoft.com/m:microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken))
Removes the subscriber matching the [SubscriptionToken](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.subscriptiontoken).

See Also
--------

<span id="seeAlsoToggle"></span>
[EventBase Class](https://msdn.microsoft.com/t:microsoft.practices.prism.pubsubevents.eventbase)

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.pubsubevents)
