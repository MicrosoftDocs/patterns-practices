---
TOCTitle: 'RegisterViewWithRegion Method (String, Func(Object))'
Title: 'RegionViewRegistry.RegisterViewWithRegion Method (String, Func(Object)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.RegisterViewWithRegion(System.String,System.Func{System.Object})'
ms:mtpsurl: 'regionviewregistry-registerviewwithregion-method-mspp-regions.md'
---

# RegionViewRegistry.RegisterViewWithRegion Method (String, Func&lt;Object&gt;)

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public void RegisterViewWithRegion(
	string regionName,
	Func<Object> getContentDelegate
)
```

### Parameters

*regionName*  

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Region name to which the *getContentDelegate* will be registered.

*getContentDelegate*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

Delegate used to retrieve the content associated with the *regionName*.

### Implements

[IRegionViewRegistry.RegisterViewWithRegion(String, Func&lt;Object&gt;)](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-string-func-object-mspp-regions)

## See Also

[RegionViewRegistry Class](/patterns-practices/reference/regionviewregistry-class-mspp-regions)<br/>
[RegionViewRegistry Members](/patterns-practices/reference/regionviewregistry-members-mspp-regions)<br/>
[RegisterViewWithRegion Overload](/patterns-practices/reference/regionviewregistry-registerviewwithregion-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>

# RegionViewRegistry.RegisterViewWithRegion Method (String, Func(Of Object))

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Sub RegisterViewWithRegion ( 
	regionName As String,
	getContentDelegate As Func(Of Object)
)
```

### Parameters

*regionName*  

Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Region name to which the *getContentDelegate* will be registered.

*getContentDelegate*  

Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

Delegate used to retrieve the content associated with the *regionName*.

### Implements

[IRegionViewRegistry.RegisterViewWithRegion(String, Func(Of Object))](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-string-func-object-mspp-regions)

## See Also

[RegionViewRegistry Class](/patterns-practices/reference/regionviewregistry-class-mspp-regions)<br/>
[RegionViewRegistry Members](/patterns-practices/reference/regionviewregistry-members-mspp-regions)<br/>
[RegisterViewWithRegion Overload](/patterns-practices/reference/regionviewregistry-registerviewwithregion-method-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>