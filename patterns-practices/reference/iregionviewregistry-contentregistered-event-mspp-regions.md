---
TOCTitle: ContentRegistered Event
Title: 'IRegionViewRegistry.ContentRegistered Event (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'E:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.ContentRegistered'
ms:mtpsurl: 'iregionviewregistry-contentregistered-event-mspp-regions.md'
---


# IRegionViewRegistry.ContentRegistered Event

Event triggered when a content is registered to a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
event EventHandler<ViewRegisteredEventArgs> ContentRegistered
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)&lt;[ViewRegisteredEventArgs](/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions)&gt;

## Syntax

```VB
'Declaration
Event ContentRegistered As EventHandler(Of ViewRegisteredEventArgs)
```

### Value

Type: [System.EventHandler](http://msdn.microsoft.com/en-us/library/db0etb8x)(Of [ViewRegisteredEventArgs](/patterns-practices/reference/viewregisteredeventargs-class-mspp-regions))

## Remarks

 This event uses weak references to the event handler to prevent this service (typically a singleton) of keeping the target element longer than expected.

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)<br/>
[IRegionViewRegistry Members](/patterns-practices/reference/iregionviewregistry-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)