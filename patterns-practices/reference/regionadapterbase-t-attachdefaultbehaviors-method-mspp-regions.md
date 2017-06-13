---
TOCTitle: AttachDefaultBehaviors Method
Title: 'RegionAdapterBase(T).AttachDefaultBehaviors Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionAdapterBase\`1.AttachDefaultBehaviors(Microsoft.Practices.Prism.Regions.IRegion,\`0)'
ms:mtpsurl: 'regionadapterbase-t-attachdefaultbehaviors-method-mspp-regions.md'
---


# RegionAdapterBase&lt;T&gt;.AttachDefaultBehaviors Method 

This method adds the default behaviors by using the [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions) object.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected virtual void AttachDefaultBehaviors(
	IRegion region,
	T regionTarget
)
```

### Parameters

_region_  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region being used.

_regionTarget_  
Type: [T](/patterns-practices/reference/iregion-interface-mspp-regions)  
The object to adapt.

## See Also

[RegionAdapterBase&lt;T&gt; Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)<br/>
[RegionAdapterBase&lt;T&gt; Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>


# RegionAdapterBase(Of T).AttachDefaultBehaviors Method 

This method adds the default behaviors by using the [IRegionBehaviorFactory](/patterns-practices/reference/iregionbehaviorfactory-interface-mspp-regions) object.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Protected Overridable Sub AttachDefaultBehaviors ( 
	region As IRegion,
	regionTarget As T
)
```

### Parameters

_region_  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The region being used.

_regionTarget_  
Type: [T](/patterns-practices/reference/iregion-interface-mspp-regions)  
The object to adapt.

## See Also

[RegionAdapterBase(Of T) Class](/patterns-practices/reference/regionadapterbase-t-class-mspp-regions)<br/>
[RegionAdapterBase(Of T) Members](/patterns-practices/reference/regionadapterbase-t-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>