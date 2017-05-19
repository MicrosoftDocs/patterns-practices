---
TOCTitle: Deactivate Method
Title: 'AllActiveRegion.Deactivate Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.AllActiveRegion.Deactivate(System.Object)'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405932(v=PandP.50)'
---

# AllActiveRegion.Deactivate Method

Deactive is not valid in this Region. This method will always throw [InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a).

**Namespace:** [Microsoft.Practices.Prism.Regions](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))

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

[IRegion.Deactivate(Object)](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.iregion.deactivate(v=pandp.50))

## Exceptions

| Exception                                                                                 | Condition                         |
|-------------------------------------------------------------------------------------------|-----------------------------------|
| [System.InvalidOperationException](http://msdn.microsoft.com/en-us/library/2asft85a) | Every time this method is called. |

## See Also

[AllActiveRegion Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.allactiveregion(v=pandp.50))

[AllActiveRegion Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions.allactiveregion_members(v=pandp.50))

[Microsoft.Practices.Prism.Regions Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.regions(v=pandp.50))