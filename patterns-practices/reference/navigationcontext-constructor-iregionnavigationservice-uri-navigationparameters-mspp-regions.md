---
TOCTitle: 'NavigationContext Constructor (IRegionNavigationService, Uri, NavigationParameters)'
Title: 'NavigationContext Constructor (IRegionNavigationService, Uri, NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationContext.\#ctor(Microsoft.Practices.Prism.Regions.IRegionNavigationService,System.Uri,Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'navigationcontext-constructor-iregionnavigationservice-uri-mspp-regions.md'
---

# NavigationContext Constructor (IRegionNavigationService, Uri, NavigationParameters)

Initializes a new instance of the [NavigationContext](/patterns-practices/reference/navigationcontext-class-mspp-regions) class for a region name and a [Uri](/patterns-practices/reference/navigationcontext-uri-property-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public NavigationContext(
	IRegionNavigationService navigationService,
	Uri uri,
	NavigationParameters navigationParameters
)
```

```VB
'Declaration
Public Sub New ( 
	navigationService As IRegionNavigationService,
	uri As Uri,
	navigationParameters As NavigationParameters
)
```

### Parameters

*navigationService*  

Type: [Microsoft.Practices.Prism.Regions.IRegionNavigationService](/patterns-practices/reference/iregionnavigationservice-interface-mspp-regions)

The navigation service.

*uri*  

Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)

The Uri.

*navigationParameters*  

Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)

The navigation parameters.

## See Also

[NavigationContext Class](/patterns-practices/reference/navigationcontext-class-mspp-regions)  
[NavigationContext Members](/patterns-practices/reference/navigationcontext-members-mspp-regions)  
NavigationContext Overload  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  