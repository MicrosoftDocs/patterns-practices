---
TOCTitle: Deactivate Method
Title: 'AllActiveRegion.Deactivate Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.AllActiveRegion.Deactivate(System.Object)'
ms:mtpsurl: 'allactiveregion-deactivate-method-mspp-regions.md'
---

# AllActiveRegion.Deactivate Method

Deactive is not valid in this Region. This method will always throw [InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public override void Deactivate(
	Object view
)
```

```VB
'Declaration
Public Overrides Sub Deactivate ( 
	view As Object
)
```
### Parameters

*view*

    Type: [System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
    The view to deactivate.

### Implements

[IRegion.Deactivate(Object)](/patterns-practices/reference/iregion-deactivate-method-mspp-regions)

## Exceptions

| Exception                                                                                 | Condition                         |
|-------------------------------------------------------------------------------------------|-----------------------------------|
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | Every time this method is called. |

## See Also

[AllActiveRegion Class](/patterns-practices/reference/allactiveregion-class-mspp-regions)

[AllActiveRegion Members](/patterns-practices/reference/allactiveregion-members-mspp-regions)

[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)