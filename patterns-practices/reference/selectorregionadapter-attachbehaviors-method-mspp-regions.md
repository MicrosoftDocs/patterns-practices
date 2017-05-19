---
TOCTitle: AttachBehaviors Method
Title: 'SelectorRegionAdapter.AttachBehaviors Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.SelectorRegionAdapter.AttachBehaviors(Microsoft.Practices.Prism.Regions.IRegion,System.Windows.Controls.Primitives.Selector)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg418993(v=PandP.50)'
---

Prism Class Library

SelectorRegionAdapter.AttachBehaviors Method
================================================

Attach new behaviors.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>protected override void AttachBehaviors( IRegion region, Selector regionTarget )Protected Overrides Sub AttachBehaviors ( region As IRegion, regionTarget As Selector )
#### Parameters

region  
Type: [Microsoft.Practices.Prism.Regions.IRegion](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion(v=pandp.50))
The region being used.

regionTarget  
Type: [System.Windows.Controls.Primitives.Selector](http://msdn2.microsoft.com/en-us/library/ms595227)
The object to adapt.

Remarks
-------

<span id="remarksToggle"></span> This class attaches the base behaviors and also listens for changes in the activity of the region or the control selection and keeps the in sync.

See Also
--------


[SelectorRegionAdapter Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.selectorregionadapter(v=pandp.50))

[SelectorRegionAdapter Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.selectorregionadapter_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))
