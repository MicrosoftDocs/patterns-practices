---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult))'
Title: 'INavigateAsync.RequestNavigate Method (Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigateAsync.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405952(v=PandP.50)'
---

Prism Class Library

INavigateAsync.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;)
==============================================================================================

Initiates navigation to the target specified by the [Uri](http://msdn.microsoft.com/en-us/library/txt7706a).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationresult(v=pandp.50))&gt;

The callback executed when the navigation request is completed.

Remarks
-------

<span id="remarksToggle"></span> Convenience overloads for this method can be found as extension methods on the [NavigationAsyncExtensions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationasyncextensions(v=pandp.50)) class.

See Also
--------


[INavigateAsync Interface](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigateasync(v=pandp.50))

[INavigateAsync Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigateasync_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.inavigateasync.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
