---
TOCTitle: 'CreateFromXaml Method (Stream)'
Title: 'ModuleCatalog.CreateFromXaml Method (Stream) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.CreateFromXaml(System.IO.Stream)'
ms:mtpsurl: 'modulecatalog-createfromxaml-method-mspp-modularity.md'
---

# ModuleCatalog.CreateFromXaml Method (Stream)

Creates a [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) from XAML.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static ModuleCatalog CreateFromXaml(
	Stream xamlStream
)
```
```VB
'Declaration
Public Shared Function CreateFromXaml ( 
	xamlStream As Stream
) As ModuleCatalog
```

### Parameters

*xamlStream*  
Type: [System.IO.Stream](http://msdn.microsoft.com/en-us/library/8f86tw9e)   
[Stream](http://msdn.microsoft.com/en-us/library/8f86tw9e) that contains the XAML declaration of the catalog.

### Return Value

Type: [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)   
An instance of [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) built from the XAML.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[CreateFromXaml Overload](/patterns-practices/reference/modulecatalog-createfromxaml-method-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  