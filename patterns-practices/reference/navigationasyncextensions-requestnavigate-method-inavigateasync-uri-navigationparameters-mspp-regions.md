---
TOCTitle: 'RequestNavigate Method (INavigateAsync, Uri, NavigationParameters)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri, NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.Uri,Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736248(v=PandP.50)'
---

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri, NavigationParameters)

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RequestNavigate(
	this INavigateAsync navigation,
	Uri target,
	NavigationParameters navigationParameters
)
```

```VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	navigation As INavigateAsync,
	target As Uri,
	navigationParameters As NavigationParameters
)
```

### Parameters

*navigation*  
The navigation object.

*target*<br/>
A Uri that represents the target where the region will navigate.

*navigationParameters*  
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigateasync(v=pandp.50)). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationasyncextensions(v=pandp.50))

[NavigationAsyncExtensions Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationasyncextensions_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
