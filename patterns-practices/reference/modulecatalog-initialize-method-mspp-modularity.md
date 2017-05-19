---
TOCTitle: Initialize Method
Title: 'ModuleCatalog.Initialize Method (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.Initialize'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405880(v=PandP.50)'
---

Prism Class Library

ModuleCatalog.Initialize Method
===================================

Initializes the catalog, which may load and validate the modules.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll) Version: 5.0.0.0 (5.0.0.0)
Syntax
------

<span id="syntaxToggle"></span>public virtual void Initialize()Public Overridable Sub Initialize
#### Implements

[IModuleCatalog.Initialize()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.imodulecatalog.initialize)

Exceptions
----------

<span id="exceptionsToggle"></span>
| Exception                                                                                                                                             | Condition                                                                                                                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Microsoft.Practices.Prism.Modularity.ModularityException](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modularityexception) | When validation of the [ModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog) fails, because this method calls [Validate()()()](https://msdn.microsoft.com/m:microsoft.practices.prism.modularity.modulecatalog.validate). |

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
