---
TOCTitle: MefContentControlRegionAdapter Class
Title: 'MefContentControlRegionAdapter Class (Microsoft.Practices.Prism.MefExtensions.Regions)'
ms:assetid: 'T:Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431460(v=PandP.50)'
---

Prism Class Library

MefContentControlRegionAdapter Class
====================================

Exports the ContentControlRegionAdapter using the Managed Extensibility Framework (MEF).

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class MefContentControlRegionAdapter : ContentControlRegionAdapterPublic Class MefContentControlRegionAdapter Inherits ContentControlRegionAdapter

Remarks
-------

<span id="remarksToggle"></span> This allows the [ConfigureContainer()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.mefextensions.mefbootstrapper.configurecontainer) to provide this class as a default implementation. If another implementation is found, this export will not be used.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Regions.RegionAdapterBase](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionadapterbase%601)&lt;(Of &lt;([ContentControl](http://msdn.microsoft.com/en-us/library/ms609797)&gt;)&gt;)
    [Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.contentcontrolregionadapter)
      Microsoft.Practices.Prism.MefExtensions.Regions.MefContentControlRegionAdapter

See Also
--------


[MefContentControlRegionAdapter Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.regions.mefcontentcontrolregionadapter)

[Microsoft.Practices.Prism.MefExtensions.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.regions)
