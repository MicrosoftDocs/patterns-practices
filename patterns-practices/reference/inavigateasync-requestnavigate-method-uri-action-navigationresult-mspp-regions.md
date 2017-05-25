---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult))'
Title: 'INavigateAsync.RequestNavigate Method (Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigateAsync.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'inavigateasync-requestnavigate-method-mspp-regions.md'
---

Prism Class Library

INavigateAsync.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;)
==============================================================================================

Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)


## Syntax


```C#
void RequestNavigate(
	Uri target,
	Action<NavigationResult> navigationCallback
)
```
```VB
'Declaration
Sub RequestNavigate ( 
	target As Uri,
	navigationCallback As Action(Of NavigationResult)
)
```

### Parameters

*target*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)

The navigation target

*navigationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](navigationresult-class-mspp-regions.md)&gt;

The callback executed when the navigation request is completed.

Remarks
-------

 Convenience overloads for this method can be found as extension methods on the [NavigationAsyncExtensions](navigationasyncextensions-class-mspp-regions.md) class.

See Also
--------


[INavigateAsync Interface](inavigateasync-interface-mspp-regions.md)

[INavigateAsync Members](inavigateasync-members-mspp-regions.md)

[RequestNavigate Overload](inavigateasync-requestnavigate-method-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
