---
TOCTitle: Subscribe Method
Title: 'CompositePresentationEvent(TPayload).Subscribe Method (Microsoft.Practices.Prism.Events)'
ms:assetid: 'Overload:Microsoft.Practices.Prism.Events.CompositePresentationEvent\`1.Subscribe'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg419057(v=PandP.50)'
---

Prism Class Library

CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)..::.Subscribe Method
==============================================================================

Include Protected Members
Include Inherited Members

Overload List
-------------

<span id="overloadMembersTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg419057.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d))
Subscribes a delegate to an event that will be published on the PublisherThread. [CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601) will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Gg419057.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption))
Subscribes a delegate to an event. CompositePresentationEvent will maintain a [WeakReference](http://msdn2.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.

![](https://msdn.microsoft.com/en-us/Gg419057.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2csystem.boolean))
Subscribes a delegate to an event that will be published on the PublisherThread.

![](https://msdn.microsoft.com/en-us/Gg419057.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean))
Subscribes a delegate to an event.

![](https://msdn.microsoft.com/en-us/Gg419057.pubmethod(en-us,PandP.50).gif "Public method")
[Subscribe(Action&lt;(Of &lt;(TPayload&gt;)&gt;), ThreadOption, Boolean, Predicate&lt;(Of &lt;(TPayload&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.events.compositepresentationevent%601.subscribe(system.action%7b%600%7d%2cmicrosoft.practices.prism.pubsubevents.threadoption%2csystem.boolean%2csystem.predicate%7b%600%7d))
Subscribes a delegate to an event.

See Also
--------

<span id="seeAlsoToggle"></span>
[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Class](https://msdn.microsoft.com/t:microsoft.practices.prism.events.compositepresentationevent%601)

[CompositePresentationEvent&lt;(Of &lt;(TPayload&gt;)&gt;) Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.events.compositepresentationevent%601)

[Microsoft.Practices.Prism.Events Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.events)
