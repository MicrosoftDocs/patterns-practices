---
TOCTitle: UpdatingRegions Event
Title: 'RegionManager.UpdatingRegions Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.RegionManager.UpdatingRegions'
ms:mtpsurl: 'regionmanager-updatingregions-event-mspp-regions.md'
---


# RegionManager.UpdatingRegions Event

Notification used by attached behaviors to update the region managers appropriatelly if needed to.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static event EventHandler UpdatingRegions
```

```VB
'Declaration
Public Shared Event UpdatingRegions As EventHandler
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)


## Remarks

This event uses weak references to the event handler to prevent this static event of keeping the target element longer than expected.

## See Also

[RegionManager Class](/patterns-practices/reference/regionmanager-class-mspp-regions)<br/>
[RegionManager Members](/patterns-practices/reference/regionmanager-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)