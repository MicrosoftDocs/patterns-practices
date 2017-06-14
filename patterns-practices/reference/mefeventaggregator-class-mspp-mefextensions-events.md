---
TOCTitle: MefEventAggregator Class
Title: 'MefEventAggregator Class (Microsoft.Practices.Prism.MefExtensions.Events)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Events.MefEventAggregator'
ms:mtpsurl: 'mefeventaggregator-class-mspp-mefextensions-events.md'
---


# MefEventAggregator Class

Exports the EventAggregator using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Events](/patterns-practices/reference/mspp-mefextensions-events-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public class MefEventAggregator : EventAggregator
```

```VB
'Declaration
Public Class MefEventAggregator
	Inherits EventAggregator
```

## Remarks

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
EventAggregator  
Microsoft.Practices.Prism.MefExtensions.Events.MefEventAggregator

## See Also

[MefEventAggregator Members](/patterns-practices/reference/mefeventaggregator-members-mspp-mefextensions-events)  
[Microsoft.Practices.Prism.MefExtensions.Events Namespace](/patterns-practices/reference/mspp-mefextensions-events-namespace)  