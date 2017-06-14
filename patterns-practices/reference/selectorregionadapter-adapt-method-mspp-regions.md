---
TOCTitle: Adapt Method
Title: 'SelectorRegionAdapter.Adapt Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.SelectorRegionAdapter.Adapt(Microsoft.Practices.Prism.Regions.IRegion,System.Windows.Controls.Primitives.Selector)'
ms:mtpsurl: 'selectorregionadapter-adapt-method-mspp-regions.md'
---

# SelectorRegionAdapter.Adapt Method

Adapts an [Selector](http://msdn.microsoft.com/en-us/library/ms595227) to an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)<br/>
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)<br/>
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected override void Adapt(
	IRegion region,
	Selector regionTarget
)
```
```VB
'Declaration
Protected Overrides Sub Adapt ( 
	region As IRegion,
	regionTarget As Selector
)
```

### Parameters

*region*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The new region being used.

*regionTarget*  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.Controls.Primitives.Selector](http://msdn.microsoft.com/en-us/library/ms595227)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The object to adapt.

## See Also

[SelectorRegionAdapter Class](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)<br/>
[SelectorRegionAdapter Members](/patterns-practices/reference/selectorregionadapter-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>