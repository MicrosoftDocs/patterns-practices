---
TOCTitle: ModuleCatalog Class
Title: 'ModuleCatalog Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleCatalog'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431490(v=PandP.50)'
---

Prism Class Library

ModuleCatalog Class
===================

The ModuleCatalog holds information about the modules that can be used by the application. Each module is described in a [ModuleInfo](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.moduleinfo) class, that records the name, type and location of the module. It also verifies that the ModuleCatalog is internally valid. That means that it does not have: Circular dependenciesMissing dependencies Invalid dependencies, such as a Module that's loaded at startup that depends on a module that might need to be retrieved. The ModuleCatalog also serves as a baseclass for more specialized Catalogs .

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


<span id="syntaxToggle"></span>[ContentPropertyAttribute("Items")\] public class ModuleCatalog : IModuleCatalog&lt;ContentPropertyAttribute("Items")&gt; Public Class ModuleCatalog Implements IModuleCatalog

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn2.microsoft.com/en-us/library/e5kfa45b)
  Microsoft.Practices.Prism.Modularity.ModuleCatalog
    [Microsoft.Practices.Prism.Modularity.ConfigurationModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.configurationmodulecatalog)
    [Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog](https://msdn.microsoft.com/t:microsoft.practices.prism.modularity.directorymodulecatalog)

See Also
--------


[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/n:microsoft.practices.prism.modularity)
