---
TOCTitle: UpdatingRegions Event
Title: 'IRegionManagerAccessor.UpdatingRegions Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.UpdatingRegions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430930(v=PandP.50)'
---

Prism Class Library

IRegionManagerAccessor..::.UpdatingRegions Event
================================================

Notification used by attached behaviors to update the region managers appropriatelly if needed to.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>event EventHandler UpdatingRegionsEvent UpdatingRegions As EventHandler
#### Value

Type: [System..::.EventHandler](http://msdn2.microsoft.com/en-us/library/xhb70ccc)

Remarks
-------

<span id="remarksToggle"></span>This event uses weak references to the event handler to prevent this static event of keeping the target element longer than expected.

See Also
--------

<span id="seeAlsoToggle"></span>
[IRegionManagerAccessor Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.iregionmanageraccessor)

[IRegionManagerAccessor Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregionmanageraccessor)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
