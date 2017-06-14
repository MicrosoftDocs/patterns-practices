---
TOCTitle: 'RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md'
---

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action&lt;NavigationResult&gt;, NavigationParameters)

Initiates navigation to the target specified by the *target*.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
   public static void RequestNavigate(
	this INavigateAsync navigation,
	string target,
	Action<NavigationResult> navigationCallback,
	NavigationParameters navigationParameters
) 
```

### Parameters

*navigation*<br/>
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)<br/>
The navigation object.

*target*<br/>
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The navigation target

*navigationCallback*<br/>
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)&gt;<br/>
The callback executed when the navigation request is completed.

*navigationParameters*<br/>
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)<br/>
An instance of NavigationParameters, which holds a collection of object parameters.

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(Of NavigationResult), NavigationParameters)

Initiates navigation to the target specified by the *target*.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
   'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	navigation As INavigateAsync,
	target As String,
	navigationCallback As Action(Of NavigationResult),
	navigationParameters As NavigationParameters
)
```

### Parameters

*navigation*<br/>
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions)<br/>
The navigation object.

*target*<br/>
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)<br/>
The navigation target

*navigationCallback*<br/>
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions))<br/>
The callback executed when the navigation request is completed.

*navigationParameters*<br/>
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/navigationparameters-class-mspp-regions)<br/>
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [INavigateAsync](/patterns-practices/reference/inavigateasync-interface-mspp-regions). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](/patterns-practices/reference/navigationasyncextensions-class-mspp-regions)<br/>
[NavigationAsyncExtensions Members](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-members-mspp-regions)<br/>
[RequestNavigate Overload](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)