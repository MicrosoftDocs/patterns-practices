---
TOCTitle: 'RequestNavigate Method (INavigateAsync, Uri, NavigationParameters)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri, NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.Uri,Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736248(v=PandP.50)'
---

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri, NavigationParameters)

Initiates navigation to the target specified by the *target*.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

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
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)<br/>
The navigation object.

*target*<br/>
Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)<br/>
A Uri that represents the target where the region will navigate.

*navigationParameters*  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)<br/>
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)<br/>
[NavigationAsyncExtensions Members](/patterns-practices/reference/navigationasyncextensions-members-mspp-regions)<br/>
[RequestNavigate Overload](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>