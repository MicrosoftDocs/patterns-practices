---
TOCTitle: CreateInstance Method
Title: 'RegionViewRegistry.CreateInstance Method (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'M:Microsoft.Practices.Prism.Regions.RegionViewRegistry.CreateInstance(System.Type)'
ms:mtpsurl: 'regionviewregistry-createinstance-method-mspp-regions.md'
---
# RegionViewRegistry.CreateInstance Method

Creates an instance of a registered view [Type](http://msdn.microsoft.com/en-us/library/42892f65).

**Namespace:** [Microsoft.Practices.Prism.Regions](/patterns-practices/reference/mspp-regions-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual Object CreateInstance(
	Type type
)
```

```VB
'Declaration
Protected Overridable Function CreateInstance ( 
	type As Type
) As Object
```

### Parameters

*type*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
Type of the registered view.

### Return Value

Type: [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
Instance of the registered view.

## See Also

[RegionViewRegistry Class](/patterns-practices/reference/regionviewregistry-class-mspp-regions)  
[RegionViewRegistry Members](/patterns-practices/reference/regionviewregistry-members-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)  

