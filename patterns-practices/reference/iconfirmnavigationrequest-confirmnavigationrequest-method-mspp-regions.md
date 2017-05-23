---
TOCTitle: ConfirmNavigationRequest Method
Title: 'IConfirmNavigationRequest.ConfirmNavigationRequest Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IConfirmNavigationRequest.ConfirmNavigationRequest(Microsoft.Practices.Prism.Regions.NavigationContext,System.Action{System.Boolean})'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405951(v=PandP.50)'
---

Prism Class Library

IConfirmNavigationRequest.ConfirmNavigationRequest Method
=============================================================

Determines whether this instance accepts being navigated away from.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


void ConfirmNavigationRequest( NavigationContext navigationContext, Action&lt;bool&gt; continuationCallback )Sub ConfirmNavigationRequest ( navigationContext As NavigationContext, continuationCallback As Action(Of Boolean) )

### Parameters

navigationContext  
Type: [Microsoft.Practices.Prism.Regions.NavigationContext](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationcontext)
The navigation context.

continuationCallback  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([Boolean](http://msdn.microsoft.com/en-us/library/a28wyd50)&gt;)&gt;)
The callback to indicate when navigation can proceed.

Remarks
-------

<span id="remarksToggle"></span> Implementors of this method do not need to invoke the callback before this method is completed, but they must ensure the callback is eventually invoked.

See Also
--------


[IConfirmNavigationRequest Interface](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iconfirmnavigationrequest)

[IConfirmNavigationRequest Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.iconfirmnavigationrequest)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
