---
TOCTitle: DirectoryModuleCatalog Class
Title: 'DirectoryModuleCatalog Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg431475(v=PandP.50)'
---

Prism Class Library

DirectoryModuleCatalog Class
============================

Represets a catalog created from a directory on disk.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public class DirectoryModuleCatalog : ModuleCatalogPublic Class DirectoryModuleCatalog Inherits ModuleCatalog

Remarks
-------

 The directory catalog will scan the contents of a directory, locating classes that implement [IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule) and add them to the catalog based on contents in their associated [ModuleAttribute](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleattribute). Assemblies are loaded into a new application domain with ReflectionOnlyLoad. The application domain is destroyed once the assemblies have been discovered. The diretory catalog does not continue to monitor the directory after it has created the initialze catalog.

Inheritance Hierarchy
---------------------

<span id="familyToggle"></span>[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)
  [Microsoft.Practices.Prism.Modularity.ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)
    Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog

See Also
--------


[DirectoryModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.directorymodulecatalog)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
