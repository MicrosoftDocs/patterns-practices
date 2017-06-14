---
TOCTitle: 'AddModule Method (ModuleInfo)'
Title: 'ModuleCatalog.AddModule Method (ModuleInfo) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(Microsoft.Practices.Prism.Modularity.ModuleInfo)'
ms:mtpsurl: 'addmodule-mthd-str-str-initializationmode-str.md'
---

# ModuleCatalog.AddModule Method (ModuleInfo)

Adds a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to the [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity).

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public virtual void AddModule(
	ModuleInfo moduleInfo
)
```

```VB
'Declaration
Public Overridable Sub AddModule ( 
	moduleInfo As ModuleInfo
)
```

### Parameters

*moduleInfo*  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity)  
The [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) to add.

### Return Value

Type:  
The [ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity) for easily adding multiple modules.
### Implements

[IModuleCatalog.AddModule(ModuleInfo)](/patterns-practices/reference/imodulecatalog-addmodule-method-mspp-modularity)

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[AddModule Overload](/patterns-practices/reference/modulecatalog-addmodule-method-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  

