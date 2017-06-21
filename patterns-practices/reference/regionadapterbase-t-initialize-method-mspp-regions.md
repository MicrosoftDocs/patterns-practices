---
TOCTitle: Initialize Method
Title: 'RegionAdapterBase(T).Initialize Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.Initialize(\`0,System.String)'
ms:mtpsurl: 'regionadapterbase-t-initialize-method-mspp-regions.md'
---


# RegionAdapterBase&lt;T&gt;.Initialize Method

Adapts an object and binds it to a new [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public IRegion Initialize( T regionTarget, string regionName )
```

### Parameters

*regionTarget*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [T](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The object to adapt.

*regionName*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the region to be created.

### Return Value

Type: [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The new instance of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that the *regionTarget* is bound to.

## See Also

[RegionAdapterBase&lt;T&gt; Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)  
[RegionAdapterBase&lt;T&gt; Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

# RegionAdapterBase(Of T).Initialize Method

Adapts an object and binds it to a new [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function Initialize ( regionTarget As T, regionName As String ) As IRegion
```

### Parameters

*regionTarget*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [T](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The object to adapt.

*regionName*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the region to be created.

### Return Value

Type: [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The new instance of [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions) that the *regionTarget* is bound to.

## See Also

[RegionAdapterBase(Of T) Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)  
[RegionAdapterBase(Of T) Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  