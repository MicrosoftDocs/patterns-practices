---
TOCTitle: IRegion Properties
Title: 'IRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.IRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431195(v=PandP.50)'
---

Prism Class Library

IRegion Properties
==================

Include Protected Members
Include Inherited Members

The [IRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[ActiveViews](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.activeviews)
Gets a readonly view of the collection of all the active views in the region.

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[Behaviors](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.behaviors)
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[Context](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.context)
Gets or sets a context for the region. This value can be used by the user to share context with the views.

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[Name](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.name)
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager).

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[NavigationService](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.navigationservice)
Gets or sets the navigation service.

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManager](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.regionmanager)
Gets or sets the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[SortComparison](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.sortcomparison)
Gets or sets the comparison used to sort the views.

![](https://msdn.microsoft.com/en-us/Gg431195.pubproperty(en-us,PandP.50).gif "Public property")
[Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.iregion.views)
Gets a readonly view of the collection of views in the region.

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegion Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
