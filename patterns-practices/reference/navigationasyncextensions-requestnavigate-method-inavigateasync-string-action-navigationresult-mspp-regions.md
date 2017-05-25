---
TOCTitle: 'RequestNavigate Method (INavigateAsync, String, Action(NavigationResult))'
Title: 'NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.NavigationAsyncExtensions.RequestNavigate(Microsoft.Practices.Prism.Regions.INavigateAsync,System.String,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md'
---

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action&lt;NavigationResult&gt;)

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C# 
public static void RequestNavigate(
	this INavigateAsync navigation,
	string target,
	Action<NavigationResult> navigationCallback
)
```


### Parameters

*navigation*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](inavigateasync-interface-mspp-regions.md)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation object.

*target*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation target

*navigationCallback*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](navigationresult-class-mspp-regions.md)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The callback executed when the navigation request is completed.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](inavigateasync-interface-mspp-regions.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](https://msdn.microsoft.com/en-us/library/bb383977.aspx).

# NavigationAsyncExtensions.RequestNavigate Method (INavigateAsync, String, Action(Of NavigationResult))

Initiates navigation to the target specified by the target.

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB 
'Declaration
<ExtensionAttribute> 
Public Shared Sub RequestNavigate ( 
	navigation As INavigateAsync,
	target As String,
	navigationCallback As Action(Of NavigationResult)
)
```


### Parameters

*navigation*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.INavigateAsync](inavigateasync-interface-mspp-regions.md)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation object.

*target*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The navigation target

*navigationCallback*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](navigationresult-class-mspp-regions.md))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The callback executed when the navigation request is completed.

### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [INavigateAsync](inavigateasync-interface-mspp-regions.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](https://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](https://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also

[NavigationAsyncExtensions Class](navigationasyncextensions-class-mspp-regions.md)

[NavigationAsyncExtensions Members](navigationasyncextensions-members-mspp-regions.md)

[RequestNavigate Overload](navigationasyncextensions-requestnavigate-method-inavigateasync-string-action-navigationresult-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
