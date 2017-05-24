---
TOCTitle: UpdatingRegions Event
Title: 'RegionManager.UpdatingRegions Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.RegionManager.UpdatingRegions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430936(v=PandP.50)'
---

Prism Class Library

RegionManager.UpdatingRegions Event
=======================================

Notification used by attached behaviors to update the region managers appropriatelly if needed to.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static event EventHandler UpdatingRegionsPublic Shared Event UpdatingRegions As EventHandler
### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)

Remarks
-------

This event uses weak references to the event handler to prevent this static event of keeping the target element longer than expected.

See Also
--------


[RegionManager Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.regionmanager)

[RegionManager Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionmanager)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
