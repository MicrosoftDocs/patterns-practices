---
TOCTitle: 'CreateFromXaml Method (Uri)'
Title: 'ModuleCatalog.CreateFromXaml Method (Uri) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.CreateFromXaml(System.Uri)'
ms:mtpsurl: 'modulecatalog-createfromxaml-method-mspp-modularity.md'
---


# ModuleCatalog.CreateFromXaml Method (Uri)

Creates a [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) from a XAML included as an Application Resource.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public static ModuleCatalog CreateFromXaml(
	Uri builderResourceUri
)
```

```VB
'Declaration
Public Shared Function CreateFromXaml ( 
	builderResourceUri As Uri
) As ModuleCatalog
```

### Parameters

*builderResourceUri*   
Type: [System.Uri](http://msdn.microsoft.com/en-us/library/txt7706a)   
Relative [Uri](http://msdn.microsoft.com/en-us/library/txt7706a) that identifies the XAML included as an Application Resource.

### Return Value

Type: [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)   
An instance of [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) build from the XAML.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)<br/>
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)<br/>
[CreateFromXaml Overload](/patterns-practices/reference/modulecatalog-createfromxaml-method-mspp-modularity)<br/>
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)<br/>