---
TOCTitle: 'RequestNavigate Method (IRegionManager, String, Uri)'
Title: 'RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionManagerExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.IRegionManager,System.String,System.Uri)'
ms:mtpsurl: 'regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions.md'
---

Prism Class Library

# RegionManagerExtensions.RequestNavigate Method (IRegionManager, String, Uri)

Navigates the specified region manager.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RequestNavigate(
	this IRegionManager regionManager,
	string regionName,
	Uri source
)
```
```VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	regionManager As IRegionManager,
	regionName As String,
	source As Uri
)
```


### Parameters

*regionManager*  
Type: [Microsoft.Practices.Prism.Regions.IRegionManager](iregionmanager-interface-mspp-regions.md)

The regionmanager that this extension method effects.

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the region to call Navigate on.

*source*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)

The URI of the content to display.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [IRegionManager](iregionmanager-interface-mspp-regions.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also


[RegionManagerExtensions Class](regionmanagerextensions-class-mspp-regions.md)

[RegionManagerExtensions Members](regionmanagerextensions-members-mspp-regions.md)

[RequestNavigate Overload](regionmanagerextensions-requestnavigate-method-iregionmanager-string-string-action-navigationresult-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
