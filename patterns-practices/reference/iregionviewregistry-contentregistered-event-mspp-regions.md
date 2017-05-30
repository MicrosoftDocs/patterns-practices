---
TOCTitle: ContentRegistered Event
Title: 'IRegionViewRegistry.ContentRegistered Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.ContentRegistered'
ms:mtpsurl: 'iregionviewregistry-contentregistered-event-mspp-regions.md'
---

# IRegionViewRegistry.ContentRegistered Event

Event triggered when a content is registered to a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
event EventHandler&lt;ViewRegisteredEventArgs&gt; ContentRegisteredEvent ContentRegistered As EventHandler(Of ViewRegisteredEventArgs)
### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;(Of &lt;([ViewRegisteredEventArgs](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.viewregisteredeventargs)&gt;)&gt;)

## Remarks

 This event uses weak references to the event handler to prevent this service (typically a singleton) of keeping the target element longer than expected.

## See Also
[IRegionViewRegistry Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionviewregistry)

[IRegionViewRegistry Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iregionviewregistry)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
