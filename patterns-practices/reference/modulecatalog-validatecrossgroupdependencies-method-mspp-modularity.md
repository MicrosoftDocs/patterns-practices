---
TOCTitle: ValidateCrossGroupDependencies Method
Title: 'ModuleCatalog.ValidateCrossGroupDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.ValidateCrossGroupDependencies'
ms:mtpsurl: 'modulecatalog-validatecrossgroupdependencies-method-mspp-modularity.md'
---


# ModuleCatalog.ValidateCrossGroupDependencies Method

Ensures that there are no dependencies between modules on different groups.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax
```C#
protected virtual void ValidateCrossGroupDependencies()
```
```VB
'Declaration
Protected Overridable Sub ValidateCrossGroupDependencies
```

## Remarks

 A groupless module can only depend on other groupless modules. A module within a group can depend on other modules within the same group and/or on groupless modules.

## See Also

[ModuleCatalog Class](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)