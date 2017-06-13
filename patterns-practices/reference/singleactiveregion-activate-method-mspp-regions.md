---
TOCTitle: Activate Method
Title: 'SingleActiveRegion.Activate Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.SingleActiveRegion.Activate(System.Object)'
ms:mtpsurl: 'singleactiveregion-activate-method-mspp-regions.md'
---


# SingleActiveRegion.Activate Method

Marks the specified view as active.

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
public override void Activate(
	Object view
)
```
```VB
'Declaration
Public Overrides Sub Activate ( 
	view As Object
)
```

### Parameters

*view*  
Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)   
The view to activate.

### Implements

[IRegion.Activate(Object)](/patterns-practices/reference/iregion-activate-method-mspp-regions)

## Remarks

If there is an active view before calling this method, that view will be deactivated automatically.

## See Also

[SingleActiveRegion Class](/patterns-practices/reference/singleactiveregion-class-mspp-regions)<br/>
[SingleActiveRegion Members](/patterns-practices/reference/singleactiveregion-members-mspp-regions)<br/>
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)<br/>