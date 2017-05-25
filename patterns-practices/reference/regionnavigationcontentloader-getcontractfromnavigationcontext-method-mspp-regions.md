---
TOCTitle: GetContractFromNavigationContext Method
Title: 'RegionNavigationContentLoader.GetContractFromNavigationContext Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationContentLoader.GetContractFromNavigationContext(Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'regionnavigationcontentloader-getcontractfromnavigationcontext-method-mspp-regions.md'
---

# RegionNavigationContentLoader.GetContractFromNavigationContext Method

Returns the candidate TargetContract based on the [NavigationContext](navigationcontext-class-mspp-regions.md).

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

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

    Type: [Microsoft.Practices.Prism.Regions.NavigationContext](navigationcontext-class-mspp-regions.md)
    The navigation contract.

### Return Value

Type: [String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The candidate contract to seek within the [IRegion](iregion-interface-mspp-regions.md) and to use, if not found, when resolving from the container.

## See Also

[RegionNavigationContentLoader Class](regionnavigationcontentloader-class-mspp-regions.md)

[RegionNavigationContentLoader Members](regionnavigationcontentloader-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
