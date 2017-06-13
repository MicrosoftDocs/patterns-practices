---
TOCTitle: UpdatingRegions Event
Title: 'IRegionManagerAccessor.UpdatingRegions Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.UpdatingRegions'
ms:mtpsurl: 'iregionmanageraccessor-updatingregions-event-mspp-regions.md'
---


# IRegionManagerAccessor.UpdatingRegions Event

Notification used by attached behaviors to update the region managers appropriatelly if needed to.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
event EventHandler UpdatingRegions
```

```VB
'Declaration
Event UpdatingRegions As EventHandler
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/xhb70ccc)

## Remarks

This event uses weak references to the event handler to prevent this static event of keeping the target element longer than expected.

## See Also

[IRegionManagerAccessor Interface](/patterns-practices/reference/iregionmanageraccessor-interface-mspp-regions)<br/>
[IRegionManagerAccessor Members](/patterns-practices/reference/iregionmanageraccessor-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>