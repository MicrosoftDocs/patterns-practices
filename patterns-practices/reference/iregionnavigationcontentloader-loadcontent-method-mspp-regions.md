---
TOCTitle: LoadContent Method
Title: 'IRegionNavigationContentLoader.LoadContent Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionNavigationContentLoader.LoadContent(Microsoft.Practices.Prism.Regions.IRegion,Microsoft.Practices.Prism.Regions.NavigationContext)'
ms:mtpsurl: 'iregionnavigationcontentloader-loadcontent-method-mspp-regions.md'
---

# IRegionNavigationContentLoader.LoadContent Method

Gets the content to which the navigation request represented by navigationContext applies.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
Object LoadContent(
	IRegion region,
	NavigationContext navigationContext
)
```

```VB
'Declaration
Function LoadContent ( 
	region As IRegion,
	navigationContext As NavigationContext
) As Object
```

### Parameters

*region*<br/>
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion)<br/>
The region.

*navigationContext*<br/>
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationcontext)<br/>
The context representing the navigation request.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)<br/>
The item to be the target of the navigation request.

## Remarks

 If none of the items in the region match the target of the navigation request, a new item will be created and added to the region.

## Exceptions

<table  style="width:100%;">
<tr>
<td>Exception</td>
<td>Condition</td>
</tr>
<tr>
<td><a href="http://msdn.microsoft.com/en-us/library/2asft85a">System.InvalidOperationException</td>
<td>when a new item cannot be created for the navigation request.
</td>
</tr>
</table>

## See Also

[IRegionNavigationContentLoader Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregionnavigationcontentloader)

[IRegionNavigationContentLoader Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregionnavigationcontentloader_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)