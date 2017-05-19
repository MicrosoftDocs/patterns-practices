---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult), NavigationParameters)'
Title: 'INavigateAsync.RequestNavigate Method (Uri, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.INavigateAsync.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Dn736274(v=PandP.50)'
---

Prism Class Library

INavigateAsync.RequestNavigate Method (Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)
====================================================================================================================

Initiates navigation to the target specified by the [Uri](http://msdn2.microsoft.com/en-us/library/txt7706a).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>void RequestNavigate( Uri target, Action&lt;NavigationResult&gt; navigationCallback, NavigationParameters navigationParameters )Sub RequestNavigate ( target As Uri, navigationCallback As Action(Of NavigationResult), navigationParameters As NavigationParameters )
#### Parameters

target  
Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)
The navigation target

navigationCallback  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([NavigationResult](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationresult)&gt;)&gt;)
The callback executed when the navigation request is completed.

navigationParameters  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationparameters)
The navigation parameters specific to the navigation request.

Remarks
-------

<span id="remarksToggle"></span> Convenience overloads for this method can be found as extension methods on the [NavigationAsyncExtensions](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationasyncextensions) class.

See Also
--------

<span id="seeAlsoToggle"></span>
[INavigateAsync Interface](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.inavigateasync)

[INavigateAsync Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.inavigateasync)

[RequestNavigate Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.inavigateasync.requestnavigate)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
