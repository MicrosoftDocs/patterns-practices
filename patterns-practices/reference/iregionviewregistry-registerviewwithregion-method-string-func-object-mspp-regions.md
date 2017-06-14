---
TOCTitle: 'RegisterViewWithRegion Method (String, Func(Object))'
Title: 'IRegionViewRegistry.RegisterViewWithRegion Method (String, Func(Object)) (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.IRegionViewRegistry.RegisterViewWithRegion(System.String,System.Func{System.Object})'
ms:mtpsurl: 'iregionviewregistry-registerviewwithregion-method-mspp-regions.md'
---

# IRegionViewRegistry.RegisterViewWithRegion Method (String, Func&lt;Object&gt;)

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
void RegisterViewWithRegion(
	string regionName,
	Func<Object> getContentDelegate
)
```

### Parameters

*regionName*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Region name to which the *getContentDelegate* will be registered.

*getContentDelegate*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)&lt;[Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Delegate used to retrieve the content associated with the *regionName*.

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)  
[IRegionViewRegistry Members](/patterns-practices/reference/iregionviewregistry-members-mspp-regions)  
[RegisterViewWithRegion Overload](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

# IRegionViewRegistry.RegisterViewWithRegion Method (String, Func(Of Object))

Registers a delegate that can be used to retrieve the content associated with a region name.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Sub RegisterViewWithRegion ( 
	regionName As String,
	getContentDelegate As Func(Of Object)
)
```

### Parameters

*regionName*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Region name to which the *getContentDelegate* will be registered.

*getContentDelegate*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Func](http://msdn.microsoft.com/en-us/library/bb534960)(Of [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b))

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Delegate used to retrieve the content associated with the *regionName*.

## See Also

[IRegionViewRegistry Interface](/patterns-practices/reference/iregionviewregistry-interface-mspp-regions)  
[IRegionViewRegistry Members](/patterns-practices/reference/iregionviewregistry-members-mspp-regions)  
[RegisterViewWithRegion Overload](/patterns-practices/reference/iregionviewregistry-registerviewwithregion-method-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  
