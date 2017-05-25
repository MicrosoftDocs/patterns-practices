---
TOCTitle: UpdatingRegions Event
Title: 'IRegionManagerAccessor.UpdatingRegions Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.IRegionManagerAccessor.UpdatingRegions'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg430930(v=PandP.50)'
---

Prism Class Library

# IRegionManagerAccessor.UpdatingRegions Event

Notification used by attached behaviors to update the region managers appropriatelly if needed to.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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


[IRegionManagerAccessor Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanageraccessor(v=pandp.50))

[IRegionManagerAccessor Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionmanageraccessor_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
