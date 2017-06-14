---
TOCTitle: Adapt Method
Title: 'ContentControlRegionAdapter.Adapt Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.ContentControlRegionAdapter.Adapt(Microsoft.Practices.Prism.Regions.IRegion,System.Windows.Controls.ContentControl)'
ms:mtpsurl: 'contentcontrolregionadapter-adapt-method-mspp-regions.md'
---

# ContentControlRegionAdapter.Adapt Method

Adapts a [ContentControl](http://msdn.microsoft.com/en-us/library/ms609797) to an [IRegion](/patterns-practices/reference/iregion-interface-mspp-regions).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected override void Adapt(
	IRegion region,
	ContentControl regionTarget
)
```

```VB
'Declaration
Protected Overrides Sub Adapt ( 
	region As IRegion,
	regionTarget As ContentControl
)
```

### Parameters

*region*  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)  
The new region being used.

*regionTarget*  
Type: [System.Windows.Controls.ContentControl](http://msdn.microsoft.com/en-us/library/ms609797)  
The object to adapt.

## See Also

[ContentControlRegionAdapter Class](/patterns-practices/reference/contentcontrolregionadapter-class-mspp-regions)  
[ContentControlRegionAdapter Members](/patterns-practices/reference/contentcontrolregionadapter-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  