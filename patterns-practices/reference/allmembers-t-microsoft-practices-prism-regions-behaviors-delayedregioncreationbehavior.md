---
TOCTitle: DelayedRegionCreationBehavior Members
Title: 'DelayedRegionCreationBehavior Members (Microsoft.Practices.Prism.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.Behaviors.DelayedRegionCreationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430864(v=PandP.50)'
---

Prism Class Library

DelayedRegionCreationBehavior Members
=====================================

Include Protected Members
Include Inherited Members

The [DelayedRegionCreationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[DelayedRegionCreationBehavior](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.)
Initializes a new instance of the [DelayedRegionCreationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior) class.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[Attach](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.attach)
Start monitoring the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) and the [TargetElement](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement) to detect when the [TargetElement](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement) becomes part of the Visual Tree. When that happens, the Region will be created and the behavior will [Detach()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.detach).

![](https://msdn.microsoft.com/en-us/Gg430864.protmethod(en-us,PandP.50).gif "Protected method")
[CreateRegion](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.createregion(system.windows.dependencyobject%2csystem.string))
Method that will create the region, by calling the right [IRegionAdapter](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionadapter).

![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[Detach](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.detach)
Stop monitoring the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) and the [TargetElement](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement), so that this behavior can be garbage collected.

![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430864.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430864.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[OnUpdatingRegions](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.onupdatingregions(system.object%2csystem.eventargs))
Called when the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) is updating it's [Regions](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.regionmanager.regions) collection.

![](https://msdn.microsoft.com/en-us/Gg430864.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430864.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManagerAccessor](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.regionmanageraccessor)
Sets a class that interfaces between the [RegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionmanager) 's static properties/events and this behavior, so this behavior can be tested in isolation.

![](https://msdn.microsoft.com/en-us/Gg430864.pubproperty(en-us,PandP.50).gif "Public property")
[TargetElement](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior.targetelement)
The element that will host the Region.

See Also
--------

<span id="seeAlsoToggle"></span>
[DelayedRegionCreationBehavior Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.delayedregioncreationbehavior)

[Microsoft.Practices.Prism.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions.behaviors)
