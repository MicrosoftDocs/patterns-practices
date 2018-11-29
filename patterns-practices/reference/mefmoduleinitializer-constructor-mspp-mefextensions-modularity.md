---
TOCTitle: MefModuleInitializer Constructor
Title: 'MefModuleInitializer Constructor (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer.\#ctor(Microsoft.Practices.ServiceLocation.IServiceLocator,Microsoft.Practices.Prism.Logging.ILoggerFacade,Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection,System.ComponentModel.Composition.Hosting.AggregateCatalog)'
ms:mtpsurl: 'mefmoduleinitializer-constructor-mspp-mefextensions-modularity.md'
---

# MefModuleInitializer Constructor

Initializes a new instance of the [MefModuleInitializer](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public MefModuleInitializer(
	IServiceLocator serviceLocator,
	ILoggerFacade loggerFacade,
	DownloadedPartCatalogCollection downloadedPartCatalogs,
	AggregateCatalog aggregateCatalog
)
```

```VB
'Declaration
Public Sub New ( 
	serviceLocator As IServiceLocator,
	loggerFacade As ILoggerFacade,
	downloadedPartCatalogs As DownloadedPartCatalogCollection,
	aggregateCatalog As AggregateCatalog
)
```

### Parameters

*serviceLocator*   
Type: IServiceLocator   
The container that will be used to resolve the modules by specifying its type.

*loggerFacade*   
Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](/patterns-practices/reference/iloggerfacade-interface-mspp-logging)   
The logger to use.

*downloadedPartCatalogs*   
Type: [Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection](/patterns-practices/reference/downloadedpartcatalogcollection-class-mspp-mefextensions-modularity)   
The downloaded part catalogs.

*aggregateCatalog*   
Type: [System.ComponentModel.Composition.Hosting.AggregateCatalog](http://msdn.microsoft.com/en-us/library/dd833165)   
The aggregate catalog.

## See Also

[MefModuleInitializer Class](/patterns-practices/reference/mefmoduleinitializer-class-mspp-mefextensions-modularity)  
[MefModuleInitializer Members](/patterns-practices/reference/mefmoduleinitializer-members-mspp-mefextensions-modularity)  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  