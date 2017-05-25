---
TOCTitle: TryGet Method
Title: 'DownloadedPartCatalogCollection.TryGet Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection.TryGet(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.ComponentModel.Composition.Primitives.ComposablePartCatalog@)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405837(v=PandP.50)'
---

Prism Class Library

DownloadedPartCatalogCollection.TryGet Method
=================================================

Tries to ge the catalog for the specified module info.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public bool TryGet( ModuleInfo moduleInfo, out ComposablePartCatalog catalog )Public Function TryGet ( moduleInfo As ModuleInfo, &lt;OutAttribute&gt; ByRef catalog As ComposablePartCatalog ) As Boolean

### Parameters

moduleInfo  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo)
The module info.

catalog  
Type: [System.ComponentModel.Composition.Primitives.ComposablePartCatalog](http://msdn.microsoft.com/en-us/library/dd454614)%
The catalog.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)
true if found; otherwise false;

See Also
--------


[DownloadedPartCatalogCollection Class](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity.downloadedpartcatalogcollection)

[DownloadedPartCatalogCollection Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.downloadedpartcatalogcollection)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.mefextensions.modularity)
