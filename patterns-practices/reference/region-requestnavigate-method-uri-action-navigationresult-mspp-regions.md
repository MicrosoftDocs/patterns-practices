---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult))'
Title: 'Region.RequestNavigate Method (Uri, Action(NavigationResult)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult})'
ms:mtpsurl: 'region-requestnavigate-method-mspp-regions.md'
---

# Region.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;)

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public void RequestNavigate(
	Uri target,
	Action<NavigationResult> navigationCallback
)
```

### Parameters

*target*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The target.

*navigationCallback*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions)&gt;   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A callback to execute when the navigation request is completed.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action&lt;NavigationResult&gt;)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-mspp-regions)

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)  
[Region Members](/patterns-practices/reference/region-members-mspp-regions)  
[RequestNavigate Overload](/patterns-practices/reference/region-requestnavigate-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

# Region.RequestNavigate Method (Uri, Action (Of NavigationResult))

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```VB
'Declaration
Public Sub RequestNavigate (
	target As Uri,
	navigationCallback As Action(Of NavigationResult)
)
```

### Parameters

*target*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The target.

*navigationCallback*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](/patterns-practices/reference/navigationresult-class-mspp-regions))   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A callback to execute when the navigation request is completed.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action(Of NavigationResult))](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-mspp-regions)

## See Also

[Region Class](/patterns-practices/reference/region-class-mspp-regions)  
[Region Members](/patterns-practices/reference/region-members-mspp-regions)  
[RequestNavigate Overload](/patterns-practices/reference/region-requestnavigate-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)