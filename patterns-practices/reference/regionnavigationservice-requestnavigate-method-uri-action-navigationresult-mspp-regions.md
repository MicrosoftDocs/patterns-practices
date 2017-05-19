---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult))'
Title: 'RegionNavigationService.RequestNavigate Method (Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionNavigationService.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418978(v=PandP.50)'
---

Prism Class Library

RegionNavigationService.RequestNavigate Method (Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))
=======================================================================================================

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public void RequestNavigate( Uri target, Action&lt;NavigationResult&gt; navigationCallback )Public Sub RequestNavigate ( target As Uri, navigationCallback As Action(Of NavigationResult) )
#### Parameters

target  
Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)
The target.

navigationCallback  
Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([NavigationResult](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.navigationresult)&gt;)&gt;)
A callback to execute when the navigation request is completed.

#### Implements

[INavigateAsync.RequestNavigate(Uri, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;))](https://msdn.microsoft.com/m:microsoft.practices.prism.regions.inavigateasync.requestnavigate(system.uri%2csystem.action%7bmicrosoft.practices.prism.regions.navigationresult%7d))

See Also
--------

<span id="seeAlsoToggle"></span>
[RegionNavigationService Class](https://msdn.microsoft.com/t:microsoft.practices.prism.regions.regionnavigationservice)

[RegionNavigationService Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.regionnavigationservice)

[RequestNavigate Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.regionnavigationservice.requestnavigate)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.regions)
