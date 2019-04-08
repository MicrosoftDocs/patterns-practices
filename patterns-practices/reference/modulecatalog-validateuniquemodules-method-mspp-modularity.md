---
TOCTitle: ValidateUniqueModules Method
Title: 'ModuleCatalog.ValidateUniqueModules Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.ValidateUniqueModules'
ms:mtpsurl: 'modulecatalog-validateuniquemodules-method-mspp-modularity.md'
---


# ModuleCatalog.ValidateUniqueModules Method

Makes sure all modules have an Unique name.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual void ValidateUniqueModules()
```
```VB
'Declaration
Protected Overridable Sub ValidateUniqueModules
```

## Exceptions


| Exception                                                                                                                                                       | Condition                                                  |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity.DuplicateModuleException](/patterns-practices/reference/duplicatemoduleexception-class-mspp-modularity) | Thrown if the names of one or more modules are not unique. |

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)