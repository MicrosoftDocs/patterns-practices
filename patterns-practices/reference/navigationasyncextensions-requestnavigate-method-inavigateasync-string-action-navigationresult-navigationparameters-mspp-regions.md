---
TOCTitle: 'RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md'
---

Prism Class Library

NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action&lt;(Of &lt;(NavigationResult&gt;)&gt;), NavigationParameters)
==================================================================================================================================================

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public static void RequestNavigate( this INavigateAsync navigation, string target, Action&lt;NavigationResult&gt; navigationCallback, NavigationParameters navigationParameters )&lt;ExtensionAttribute&gt; Public Shared Sub RequestNavigate ( navigation As INavigateAsync, target As String, navigationCallback As Action(Of NavigationResult), navigationParameters As NavigationParameters )

### Parameters

navigation  
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync)
The navigation object.

target  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The navigation target

navigationCallback  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;(Of &lt;([NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult)&gt;)&gt;)
The callback executed when the navigation request is completed.

navigationParameters  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationparameters)
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

See Also
--------


[NavigationAsyncExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions)

[NavigationAsyncExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.navigationasyncextensions)

[RequestNavigate Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.regions.navigationasyncextensions.requestnavigate)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
