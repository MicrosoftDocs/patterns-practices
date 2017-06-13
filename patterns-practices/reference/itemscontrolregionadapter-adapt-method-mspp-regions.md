---
TOCTitle: Adapt Method
Title: 'ItemsControlRegionAdapter.Adapt Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.ItemsControlRegionAdapter.Adapt(Microsoft.Practices.Prism.Regions.IRegion,System.Windows.Controls.ItemsControl)'
ms:mtpsurl: 'itemscontrolregionadapter-adapt-method-mspp-regions.md'
---

# ItemsControlRegionAdapter.Adapt Method

Adapts an [ItemsControl](http://msdn.microsoft.com/en-us/library/ms611045) to an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected override void Adapt(
	IRegion region,
	ItemsControl regionTarget
)
```
```VB
'Declaration
Protected Overrides Sub Adapt ( 
	region As IRegion,
	regionTarget As ItemsControl
)
```

### Parameters

*region*  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The new region being used.

*regionTarget*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Type: [System.Windows.Controls.ItemsControl](http://msdn.microsoft.com/en-us/library/ms611045)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The object to adapt.

## See Also

[ItemsControlRegionAdapter Class](/patterns-practices/reference/itemscontrolregionadapter-class-mspp-regions)<br/>
[ItemsControlRegionAdapter Members](/patterns-practices/reference/itemscontrolregionadapter-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>