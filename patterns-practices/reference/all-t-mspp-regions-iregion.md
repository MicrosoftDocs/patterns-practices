---
TOCTitle: IRegion Members
Title: 'IRegion Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430883(v=PandP.50)'
---

Prism Class Library

IRegion Members
===============

Include Protected Members
Include Inherited Members

The [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) type exposes the following members.

Methods
-------

<span id="methodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Activate](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.activate(system.object))
Marks the specified view as active.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object, String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Add(Object, String, Boolean)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.add(system.object%2csystem.string%2csystem.boolean))
Adds a new view to the region.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Deactivate](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.deactivate(system.object))
Marks the specified view as inactive.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[GetView](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.getview(system.string))
Returns the view instance that was added to the region using a specific name.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[Remove](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.iregion.remove(system.object))
Removes the specified view from the region.

![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Inherited from [INavigateAsync](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubmethod(en-us,PandP.50).gif "Public method")
[RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Inherited from [INavigateAsync](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync).)

Extension Methods
-----------------

<span id="extensionMethodTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(Uri)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri))
Overloaded.
Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(Uri, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.uri%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)
![](https://msdn.microsoft.com/en-us/Gg430883.pubextension(en-us,PandP.50).gif "Public Extension Method")
[RequestNavigate(String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(microsoft.practices.prism.regions.inavigateasync%2csystem.string%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d%2cmicrosoft.practices.prism.regions.navigationparameters))
Overloaded.
Initiates navigation to the target specified by the target.

(Defined by [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions).)

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[ActiveViews](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.activeviews)
Gets a readonly view of the collection of all the active views in the region.

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[Behaviors](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.behaviors)
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[Context](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.context)
Gets or sets a context for the region. This value can be used by the user to share context with the views.

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[Name](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.name)
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager).

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[NavigationService](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.navigationservice)
Gets or sets the navigation service.

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManager](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.regionmanager)
Gets or sets the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[SortComparison](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.sortcomparison)
Gets or sets the comparison used to sort the views.

![](https://msdn.microsoft.com/en-us/Gg430883.pubproperty(en-us,PandP.50).gif "Public property")
[Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.views)
Gets a readonly view of the collection of views in the region.

Events
------

<span id="eventTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg430883.pubevent(en-us,PandP.50).gif "Public event")
[PropertyChanged](http://msdn2.microsoft.com/en-us/library/ms133023)
Occurs when a property value changes.

(Inherited from [INotifyPropertyChanged](http://msdn2.microsoft.com/en-us/library/ms133020).)

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegion Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
