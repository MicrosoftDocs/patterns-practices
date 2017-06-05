---
TOCTitle: 'RequestNavigate Method (Uri, Action(NavigationResult), NavigationParameters)'
Title: 'Region.RequestNavigate Method (Uri, Action(NavigationResult), NavigationParameters) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.Region.RequestNavigate(System.Uri,System.Action{Microsoft.Practices.Prism.Regions.NavigationResult},Microsoft.Practices.Prism.Regions.NavigationParameters)'
ms:mtpsurl: 'region-requestnavigate-method-mspp-regions.md'
---



# Region.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;, NavigationParameters)

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RequestNavigate(
	Uri target,
	Action<NavigationResult> navigationCallback,
	NavigationParameters navigationParameters
)
```

### Parameters

*target*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)<br/>
The target.

*navigationCallback*<br/>
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](/patterns-practices/reference/mspp-regions-namespace.navigationresult)&gt;<br/>
A callback to execute when the navigation request is completed.

*navigationParameters*  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/mspp-regions-namespace.navigationparameters)<br/>
The navigation parameters specific to the navigation request.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions)

## See Also

[Region Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region(v=pandp.50))

[Region Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)


# Region.RequestNavigate Method (Uri, Action(Of NavigationResult), NavigationParameters)

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub RequestNavigate ( 
	target As Uri,
	navigationCallback As Action(Of NavigationResult),
	navigationParameters As NavigationParameters
)
```

### Parameters

*target*  
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)<br/>
The target.

*navigationCallback*<br/>
Type: [System.Action](http://msdn.microsoft.com/en-us/library/018hxwa8)(Of [NavigationResult](/patterns-practices/reference/mspp-regions-namespace.navigationresult))<br/>
A callback to execute when the navigation request is completed.

*navigationParameters*  
Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](/patterns-practices/reference/mspp-regions-namespace.navigationparameters)<br/>
The navigation parameters specific to the navigation request.

### Implements

[INavigateAsync.RequestNavigate(Uri, Action(Of NavigationResult), NavigationParameters)](/patterns-practices/reference/inavigateasync-requestnavigate-method-uri-action-navigationresult-navigationparameters-mspp-regions)

## See Also

[Region Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region(v=pandp.50))

[Region Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.region.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/eventbase-class-mspp-pubsubevents)
