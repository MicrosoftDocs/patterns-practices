# RegionNavigationService.RequestNavigate Method (Uri, Action&lt;NavigationResult&gt;, NavigationParameters)

Initiates navigation to the specified target.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
## Syntax
```C#
public void RequestNavigate(
	Uri target,
	Action<NavigationResult> navigationCallback,
	NavigationParameters navigationParameters
)
```

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

Type: [System.Uri](http://msdn2.microsoft.com/en-us/library/txt7706a)

The target.

*navigationCallback* 

Type: [System.Action](http://msdn2.microsoft.com/en-us/library/018hxwa8)&lt;[NavigationResult](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationresult(v=pandp.50))&gt;

A callback to execute when the navigation request is completed.

*navigationParameters*

Type: [Microsoft.Practices.Prism.Regions.NavigationParameters](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.navigationparameters(v=pandp.50))

The navigation parameters specific to the navigation request.

### Implements
[INavigateAsync.RequestNavigate(Uri, Action&lt;NavigationResult&gt;, NavigationParameters)](https://msdn.microsoft.com/en-us/library/dn736274(v=pandp.50))

## See Also
[RegionNavigationService Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationservice(v=pandp.50))

[RegionNavigationService Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationservice_members(v=pandp.50))

[RequestNavigate Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.regionnavigationservice.requestnavigate(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))