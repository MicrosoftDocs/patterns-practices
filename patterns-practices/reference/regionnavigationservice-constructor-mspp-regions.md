---
TOCTitle: RegionNavigationService Constructor
Title: 'RegionNavigationService Constructor (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationService.\#ctor(Microsoft.Practices.ServiceLocation.IServiceLocator,Microsoft.Practices.Prism.Regions.IRegionNavigationContentLoader,Microsoft.Practices.Prism.Regions.IRegionNavigationJournal)'
ms:mtpsurl: 'regionnavigationservice-constructor-mspp-regions.md'
---


# RegionNavigationService Constructor

Initializes a new instance of the [RegionNavigationService](/patterns-practices/reference/regionnavigationservice-class-mspp-regions) class.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public RegionNavigationService(
	IServiceLocator serviceLocator,
	IRegionNavigationContentLoader regionNavigationContentLoader,
	IRegionNavigationJournal journal
)
```
```VB
'Declaration
Public Sub New ( 
	serviceLocator As IServiceLocator,
	regionNavigationContentLoader As IRegionNavigationContentLoader,
	journal As IRegionNavigationJournal
)
```

### Parameters

*serviceLocator*  
Type: IServiceLocator  
The service locator.

*regionNavigationContentLoader*  
Type: [Microsoft.Practices.Prism.Regions.IRegionNavigationContentLoader](/patterns-practices/reference/iregionnavigationcontentloader-interface-mspp-regions)  
The navigation target handler.

*journal*  
Type: [Microsoft.Practices.Prism.Regions.IRegionNavigationJournal](/patterns-practices/reference/iregionnavigationjournal-interface-mspp-regions)  
The journal.

## See Also

[RegionNavigationService Class](/patterns-practices/reference/regionnavigationservice-class-mspp-regions)  
[RegionNavigationService Members](/patterns-practices/reference/regionnavigationservice-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  