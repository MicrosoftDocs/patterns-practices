---
TOCTitle: 'RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters)'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md'
---


# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action&lt;NavigationResult&gt;, NavigationParameters)

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

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

*navigation*  
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync)
The navigation object.

*target*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The navigation target

*navigationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult)&gt;
The callback executed when the navigation request is completed.

*navigationParameters*  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationparameters)
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions)

[NavigationAsyncExtensions Members](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-members-mspp-regions
)

[RequestNavigate Overload](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions
)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)


# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(Of NavigationResult), NavigationParameters)

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

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

*navigation*  
Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync)
The navigation object.

*target*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The navigation target

*navigationCallback*  
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationresult))
The callback executed when the navigation request is completed.

*navigationParameters*  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationparameters)
An instance of NavigationParameters, which holds a collection of object parameters.

### Usage Note

In Visual Basic and C#, you can call this method as an instance method on any object of type [INavigateAsync](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.inavigateasync). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.navigationasyncextensions)

[NavigationAsyncExtensions Members](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-members-mspp-regions
)

[RequestNavigate Overload](https://review.docs.microsoft.com/patterns-practices/reference/navigationasyncextensions-requestnavigate-method-mspp-regions
)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)