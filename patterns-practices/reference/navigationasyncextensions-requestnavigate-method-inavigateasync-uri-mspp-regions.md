---
TOCTitle: 'RequestNavigate Method (INavigateAsync, Uri)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.Uri)'
ms:mtpsurl: 'navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md'
---

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, Uri)

Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static void RequestNavigate(
	this INavigateAsync navigation,
	Uri target
)
```
```VB
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	navigation As INavigateAsync,
	target As Uri
)
```

### Parameters

*navigation*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation object.

*target*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation target

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)<br/>
[NavigationAsyncExtensions Members](/patterns-practices/reference/navigationasyncextensions-members-mspp-regions)<br/>
[RequestNavigate Overload](/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>