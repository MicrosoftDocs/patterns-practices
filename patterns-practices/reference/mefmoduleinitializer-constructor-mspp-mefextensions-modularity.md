---
TOCTitle: MefModuleInitializer Constructor
Title: 'MefModuleInitializer Constructor (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.MefModuleInitializer.\#ctor(Microsoft.Practices.ServiceLocation.IServiceLocator,Microsoft.Practices.Prism.Logging.ILoggerFacade,Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection,System.ComponentModel.Composition.Hosting.AggregateCatalog)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405581(v=PandP.50)'
---

Prism Class Library

MefModuleInitializer Constructor
================================

Initializes a new instance of the [MefModuleInitializer](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>public MefModuleInitializer( IServiceLocator serviceLocator, ILoggerFacade loggerFacade, DownloadedPartCatalogCollection downloadedPartCatalogs, AggregateCatalog aggregateCatalog )Public Sub New ( serviceLocator As IServiceLocator, loggerFacade As ILoggerFacade, downloadedPartCatalogs As DownloadedPartCatalogCollection, aggregateCatalog As AggregateCatalog )

### Parameters

serviceLocator  
Type: IServiceLocator
The container that will be used to resolve the modules by specifying its type.

loggerFacade  
Type: [Microsoft.Practices.Prism.Logging.ILoggerFacade](https://msdn.microsoft.com/t:microsoft.practices.prism.logging.iloggerfacade)
The logger to use.

downloadedPartCatalogs  
Type: [Microsoft.Practices.Prism.MefExtensions.Modularity.DownloadedPartCatalogCollection](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.downloadedpartcatalogcollection)
The downloaded part catalogs.

aggregateCatalog  
Type: [System.ComponentModel.Composition.Hosting.AggregateCatalog](http://msdn2.microsoft.com/en-us/library/dd833165)
The aggregate catalog.

See Also
--------


[MefModuleInitializer Class](https://msdn.microsoft.com/t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[MefModuleInitializer Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.mefextensions.modularity.mefmoduleinitializer)

[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.mefextensions.modularity)
