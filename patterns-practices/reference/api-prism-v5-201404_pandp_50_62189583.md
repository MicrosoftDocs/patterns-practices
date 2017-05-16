---
TOCTitle: AllActiveRegion Properties
Title: 'AllActiveRegion Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.AllActiveRegion'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431183(v=PandP.50)'
---

Prism Class Library

AllActiveRegion Properties
==========================

Include Protected Members
Include Inherited Members

The [AllActiveRegion](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.allactiveregion) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[ActiveViews](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.allactiveregion.activeviews)
Gets a readonly view of the collection of all the active views in the region. These are all the added views.

(Overrides [Region..::.ActiveViews](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.activeviews).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[Behaviors](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.behaviors)
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[Context](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.context)
Gets or sets a context for the region. This value can be used by the user to share context with the views.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.protproperty(en-us,PandP.50).gif "Protected property")
[ItemMetadataCollection](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.itemmetadatacollection)
Gets the collection with all the views along with their metadata.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[Name](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.name)
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager).

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[NavigationService](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.navigationservice)
Gets the navigation service.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManager](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.regionmanager)
Gets or sets the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[SortComparison](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.sortcomparison)
Gets or sets the comparison used to sort the views.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)
![](https://msdn.microsoft.com/en-us/Gg431183.pubproperty(en-us,PandP.50).gif "Public property")
[Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.views)
Gets a readonly view of the collection of views in the region.

(Inherited from [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region).)

See Also
--------

<span id="seeAlsoToggle"></span>
[AllActiveRegion Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.allactiveregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
