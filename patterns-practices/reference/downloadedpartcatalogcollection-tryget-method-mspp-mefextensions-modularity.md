---
TOCTitle: TryGet Method
Title: 'DownloadedPartCatalogCollection.TryGet Method (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection.TryGet(Microsoft.Practices.Prism.Modularity.ModuleInfo,System.ComponentModel.Composition.Primitives.ComposablePartCatalog@)'
ms:mtpsurl: 'downloadedpartcatalogcollection-tryget-method-mspp-mefextensions-modularity.md'
---

# DownloadedPartCatalogCollection.TryGet Method

Tries to ge the catalog for the specified module info.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public bool TryGet(
	ModuleInfo moduleInfo,
	out ComposablePartCatalog catalog
)
```
```VB
'Declaration
Public Function TryGet ( 
	moduleInfo As ModuleInfo,
	<OutAttribute> ByRef catalog As ComposablePartCatalog
) As Boolean
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The module info.

*catalog*  
Type: [System.ComponentModel.Composition.Primitives.ComposablePartCatalog](http://msdn.microsoft.com/en-us/library/dd454614)%  
The catalog.

### Return Value

Type: [Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)  
true if found; otherwise false;

## See Also

[DownloadedPartCatalogCollection Class](/patterns-practices/reference/downloadedpartcatalogcollection-class-mspp-mefextensions-modularity)  
[DownloadedPartCatalogCollection Members](/patterns-practices/reference/downloadedpartcatalogcollection-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  