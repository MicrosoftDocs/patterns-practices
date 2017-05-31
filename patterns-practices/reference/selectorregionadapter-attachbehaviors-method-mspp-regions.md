---
TOCTitle: AttachBehaviors Method
Title: 'SelectorRegionAdapter.AttachBehaviors Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.SelectorRegionAdapter.AttachBehaviors(Microsoft.Practices.Prism.Regions.IRegion,System.Windows.Controls.Primitives.Selector)'
ms:mtpsurl: 'selectorregionadapter-attachbehaviors-method-mspp-regions.md'
---

# SelectorRegionAdapter.AttachBehaviors Method

Attach new behaviors.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
protected override void AttachBehaviors( IRegion region, Selector regionTarget )Protected Overrides Sub AttachBehaviors ( region As IRegion, regionTarget As Selector )

### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](/patterns-practices/reference/iregion-interface-mspp-regions)
The region being used.

regionTarget  
Type: [System.Windows.Controls.Primitives.Selector](http://msdn.microsoft.com/en-us/library/ms595227)
The object to adapt.

## Remarks

 This class attaches the base behaviors and also listens for changes in the activity of the region or the control selection and keeps the in sync.

## See Also
[SelectorRegionAdapter Class](/patterns-practices/reference/selectorregionadapter-class-mspp-regions)

[SelectorRegionAdapter Members](/patterns-practices/reference/selectorregionadapter-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)
