---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn683938(v=PandP.50)'
---

Prism Class Library

# PubSubEvent(Of TPayload) Methods

The [PubSubEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) type exposes the following members.

## Methods

 
Name
Description
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Contains(Action(Of TPayload))](https://msdn.microsoft.com/en-us/library/dn736237(v=pandp.50))
Returns **trueTrue** (**True** in Visual Basic) if there is a subscriber matching [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Contains(SubscriptionToken)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase.contains(v=pandp.50))
Returns **trueTrue** (**True** in Visual Basic) if there is a subscriber matching [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)).

(Inherited from [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50)))
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
[InternalPublish](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase.internalpublish(v=pandp.50))
Calls all the execution strategies exposed by the list of [IEventSubscription](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.ieventsubscription(v=pandp.50)).

(Inherited from [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50))
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[InternalSubscribe](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase.internalsubscribe(v=pandp.50))
Adds the specified [IEventSubscription](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.ieventsubscription(v=pandp.50)) to the subscribers' collection.

(Inherited from [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50)).)
![](https://msdn.microsoft.com/en-us/Dn683938.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Publish](https://msdn.microsoft.com/en-us/library/dn683930(v=pandp.50))
Publishes the [PubSubEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[	Subscribe(Action(Of TPayload))](https://msdn.microsoft.com/en-us/library/dn683969(v=pandp.50))
Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)). [PubSubEvent(Of TPayload)](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[	Subscribe(Action(Of TPayload), ThreadOption)](https://msdn.microsoft.com/en-us/library/dn736155(v=pandp.50))
Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[	Subscribe(Action(Of TPayload), Boolean)](https://msdn.microsoft.com/en-us/library/dn683949(v=pandp.50)))
Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.threadoption(v=pandp.50)).

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[	Subscribe(Action(Of TPayload), ThreadOption, Boolean)](https://msdn.microsoft.com/en-us/library/dn683942(v=pandp.50))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action(Of TPayload), ThreadOption, Boolean, Predicate(Of TPayload))](https://msdn.microsoft.com/en-us/library/dn736225(v=pandp.50))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe(Action(Of TPayload))](https://msdn.microsoft.com/en-us/library/dn736235(v=pandp.50))
Removes the first subscriber matching [Action(Of T)](http://msdn2.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.

![](https://msdn.microsoft.com/en-us/Dn683938.pubmethod(en-us,PandP.50).gif "Public method")
[Unsubscribe(SubscriptionToken)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase.unsubscribe(v=pandp.50))
Removes the subscriber matching the [SubscriptionToken](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.subscriptiontoken(v=pandp.50)).

(Inherited from [EventBase](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents.eventbase(v=pandp.50)).)

## See Also

[PubSubEvent(Of TPayload) Class](https://msdn.microsoft.com/en-us/library/dn736103(v=pandp.50)  )

[Microsoft.Practices.Prism.PubSubEvents Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.pubsubevents(v=pandp.50))
