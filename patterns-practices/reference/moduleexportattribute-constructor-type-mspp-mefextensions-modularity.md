---
TOCTitle: 'ModuleExportAttribute Constructor (Type)'
Title: 'ModuleExportAttribute Constructor (Type) (Microsoft.Practices.Prism.MefExtensions.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.MefExtensions.Modularity.ModuleExportAttribute.\#ctor(System.Type)'
ms:mtpsurl: 'moduleexportattribute-constructor-mspp-mefextensions-modularity.md'
---

# ModuleExportAttribute Constructor (Type)

Initializes a new instance of the [ModuleExportAttribute](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity) class.

**Namespace:** [Microsoft.Practices.Prism.MefExtensions.Modularity](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.MefExtensions (in Microsoft.Practices.Prism.MefExtensions.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleExportAttribute(
	Type moduleType
)
```

```VB
'Declaration
Public Sub New ( 
	moduleType As Type
)
```

### Parameters

*moduleType*  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)  
The concrete type of the module being exported. Not typeof(IModule).

## See Also

[ModuleExportAttribute Class](/patterns-practices/reference/moduleexportattribute-class-mspp-mefextensions-modularity)  
[ModuleExportAttribute Members](/patterns-practices/reference/moduleexportattribute-members-mspp-mefextensions-modularity)  
ModuleExportAttribute Overload  
[Microsoft.Practices.Prism.MefExtensions.Modularity Namespace](/patterns-practices/reference/mspp-mefextensions-modularity-namespace)  