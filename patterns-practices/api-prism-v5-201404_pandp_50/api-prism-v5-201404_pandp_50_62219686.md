---
TOCTitle: MefRegionManagerRegistrationBehavior Members
Title: 'MefRegionManagerRegistrationBehavior Members (Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors.MefRegionManagerRegistrationBehavior'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430806(v=PandP.50)'
---

Prism Class Library

MefRegionManagerRegistrationBehavior Members
============================================

Include Protected Members
Include Inherited Members

The [MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior) type exposes the following members.

Constructors
------------

<span id="constructorTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior.)
Initializes a new instance of the [MefRegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior) class

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[Attach](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.regionbehavior.attach)
Attaches the behavior to the region.

(Inherited from [RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[Equals](http://msdn2.microsoft.com/en-us/library/bsc2ak47)
Determines whether the specified [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif "Protected method")
[Finalize](http://msdn2.microsoft.com/en-us/library/4k87zsw7)
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[GetHashCode](http://msdn2.microsoft.com/en-us/library/zdee4b3y)
Serves as a hash function for a particular type.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[GetType](http://msdn2.microsoft.com/en-us/library/dfwy45w9)
Gets the [Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the current instance.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif "Protected method")
[MemberwiseClone](http://msdn2.microsoft.com/en-us/library/57ctke0a)
Creates a shallow copy of the current [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)
![](https://msdn.microsoft.com/en-us/Gg430806.protmethod(en-us,PandP.50).gif "Protected method")
[OnAttach](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.onattach)
When the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) has a name assigned, the behavior will start monitoring the ancestor controls in the element tree to look for an [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) where to register the region in.

(Inherited from [RegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[OnUpdatingRegions](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.onupdatingregions(system.object%2csystem.eventargs))
This event handler gets called when a RegionManager is requering the instances of a region to be registered if they are not already.
Remarks
-------

<span id="remarksToggle"></span>Although this is a public method to support Weak Delegates in Silverlight, it should not be called by the user.

(Inherited from [RegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubmethod(en-us,PandP.50).gif "Public method")
[ToString](http://msdn2.microsoft.com/en-us/library/7bxwbwt2)
Returns a string that represents the current object.

(Inherited from [Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif "Public property")
[HostControl](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.hostcontrol)
Gets or sets the [DependencyObject](http://msdn2.microsoft.com/en-us/library/ms589309) that the [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) is attached to.

(Inherited from [RegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif "Public property")
[IsAttached](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.regionbehavior.isattached)
Returns trueTruetruetrue (True in Visual Basic) if the behavior is attached to a region, falseFalsefalsefalse (False in Visual Basic) otherwise.

(Inherited from [RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif "Public property")
[Region](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.regionbehavior.region)
Behavior's attached region.

(Inherited from [RegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionbehavior).)
![](https://msdn.microsoft.com/en-us/Gg430806.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManagerAccessor](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior.regionmanageraccessor)
Provides an abstraction on top of the RegionManager static members.

(Inherited from [RegionManagerRegistrationBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.behaviors.regionmanagerregistrationbehavior).)

See Also
--------

<span id="seeAlsoToggle"></span>
[MefRegionManagerRegistrationBehavior Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.regions.behaviors.mefregionmanagerregistrationbehavior)

[Microsoft.Practices.Prism.MefExtensions.Regions.Behaviors Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions.behaviors)
