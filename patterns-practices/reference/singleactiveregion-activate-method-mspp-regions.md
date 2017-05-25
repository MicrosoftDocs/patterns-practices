---
TOCTitle: Activate Method
Title: 'SingleActiveRegion.Activate Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.SingleActiveRegion.Activate(System.Object)'
ms:mtpsurl: 'singleactiveregion-activate-method-mspp-regions.md'
---

Prism Class Library

SingleActiveRegion.Activate Method
======================================

Marks the specified view as active.

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public override void Activate( Object view )Public Overrides Sub Activate ( view As Object )

### Parameters

view  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
The view to activate.

### Implements

[IRegion.Activate(Object)](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.iregion.activate(system.object))

Remarks
-------

If there is an active view before calling this method, that view will be deactivated automatically.

See Also
--------


[SingleActiveRegion Class](https://msdn.microsoft.com/library/microsoft.practices.prism.regions.singleactiveregion)

[SingleActiveRegion Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.regions.singleactiveregion)

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.regions)
