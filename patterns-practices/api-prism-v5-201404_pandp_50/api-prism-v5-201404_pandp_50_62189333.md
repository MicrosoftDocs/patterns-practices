---
TOCTitle: Region Properties
Title: 'Region Properties (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'Properties.T:Microsoft.Practices.Prism.Regions.Region'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431208(v=PandP.50)'
---

Prism Class Library

Region Properties
=================

Include Protected Members
Include Inherited Members

The [Region](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region) type exposes the following members.

Properties
----------

<span id="propertyTableToggle"></span>
 
Name
Description
![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[ActiveViews](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.activeviews)
Gets a readonly view of the collection of all the active views in the region.

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[Behaviors](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.behaviors)
Gets the collection of [IRegionBehavior](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionbehavior)s that can extend the behavior of regions.

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[Context](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.context)
Gets or sets a context for the region. This value can be used by the user to share context with the views.

![](https://msdn.microsoft.com/en-us/Gg431208.protproperty(en-us,PandP.50).gif "Protected property")
[ItemMetadataCollection](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.itemmetadatacollection)
Gets the collection with all the views along with their metadata.

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[Name](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.name)
Gets the name of the region that uniequely identifies the region within a [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager).

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[NavigationService](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.navigationservice)
Gets the navigation service.

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[RegionManager](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.regionmanager)
Gets or sets the [IRegionManager](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanager) that will be passed to the views when adding them to the region, unless the view is added by specifying createRegionManagerScope as trueTruetruetrue (True in Visual Basic).

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[SortComparison](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.sortcomparison)
Gets or sets the comparison used to sort the views.

![](https://msdn.microsoft.com/en-us/Gg431208.pubproperty(en-us,PandP.50).gif "Public property")
[Views](https://msdn.microsoft.com/p:microsoft.practices.prism.regions.region.views)
Gets a readonly view of the collection of views in the region.

See Also
--------

<span id="seeAlsoToggle"></span>
[Region Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.region)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
