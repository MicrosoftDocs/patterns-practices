---
TOCTitle: MefEventAggregator Class
Title: 'MefEventAggregator Class (Microsoft.Practices.Prism.MefExtensions.Events)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Events.MefEventAggregator'
ms:mtpsurl: 'mefeventaggregator-class-mspp-mefextensions-events.md'
---

Prism Class Library

MefEventAggregator Class
========================

Exports the EventAggregator using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Events](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.events)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class MefEventAggregator : EventAggregatorPublic Class MefEventAggregator Inherits EventAggregator

Remarks
-------

 This allows the MefBootstrapper to provide this class as a default implementation. If another implementation is found, this export will not be used.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  EventAggregator
    Microsoft.Practices.Prism.MefExtensions.Events.MefEventAggregator

See Also
--------


[MefEventAggregator Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.events.mefeventaggregator)

[Microsoft.Practices.Prism.MefExtensions.Events Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.events)
