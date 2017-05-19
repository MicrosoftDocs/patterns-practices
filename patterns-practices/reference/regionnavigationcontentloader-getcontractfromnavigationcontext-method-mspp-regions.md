---
TOCTitle: GetContractFromNavigationContext Method
Title: 'RegionNavigationContentLoader.GetContractFromNavigationContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetContractFromNavigationContext(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418971(v=PandP.50)'
---

# RegionNavigationContentLoader.GetContractFromNavigationContext Method

Returns the candidate TargetContract based on the [NavigationContext](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationcontext(v=pandp.50)).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual string GetContractFromNavigationContext(
	NavigationContext navigationContext
)
```

```VB
'Declaration
Protected Overridable Function GetContractFromNavigationContext ( 
	navigationContext As NavigationContext
) As String
```


### Parameters

*navigationContext*

    Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationcontext(v=pandp.50))
    The navigation contract.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The candidate contract to seek within the [IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50)) and to use, if not found, when resolving from the container.

## See Also

[RegionNavigationContentLoader Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationcontentloader(v=pandp.50))

[RegionNavigationContentLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationcontentloader_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
