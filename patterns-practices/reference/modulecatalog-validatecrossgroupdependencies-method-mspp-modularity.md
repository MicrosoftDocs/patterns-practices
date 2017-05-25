---
TOCTitle: ValidateCrossGroupDependencies Method
Title: 'ModuleCatalog.ValidateCrossGroupDependencies Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.ValidateCrossGroupDependencies'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.validatecrossgroupdependencies(v=pandp.50)'
---

Prism Class Library

ModuleCatalog.ValidateCrossGroupDependencies Method
=======================================================

Ensures that there are no dependencies between modules on different groups.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


protected virtual void ValidateCrossGroupDependencies()Protected Overridable Sub ValidateCrossGroupDependencies

Remarks
-------

 A groupless module can only depend on other groupless modules. A module within a group can depend on other modules within the same group and/or on groupless modules.

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
