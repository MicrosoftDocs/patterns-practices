---
TOCTitle: Initialize Method
Title: 'RegionAdapterBase(T).Initialize Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.Initialize(\`0,System.String)'
ms:mtpsurl: 'regionadapterbase-t-initialize-method-mspp-regions.md'
---

# RegionAdapterBase&lt;T&gt;.Initialize Method

Adapts an object and binds it to a new [IRegion](iregion-interface-mspp-regions.md).

**Namespace:** [Microsoft.Practices.Prism.Regions](mspp-regions-namespace.md)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)
## Syntax

```C#
public IRegion Initialize( T regionTarget, string regionName )
```
```VB
'Declaration
Public Function Initialize ( regionTarget As T, regionName As String ) As IRegion
```
### Parameters

*regionTarget*  
Type: [T](regionadapterbase-t-class-mspp-regions.md)

The object to adapt.

*regionName*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

The name of the region to be created.

### Return Value

Type: [IRegion](iregion-interface-mspp-regions.md)

The new instance of [IRegion](iregion-interface-mspp-regions.md) that the *regionTarget* is bound to.

## See Also
[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Class](regionadapterbase-t-class-mspp-regions.md)

[RegionAdapterBase&lt;(Of &lt;(T&gt;)&gt;) Members](regionadapterbase-t-members-mspp-regions.md)

[Microsoft.Practices.Prism.Regions Namespace](mspp-regions-namespace.md)
