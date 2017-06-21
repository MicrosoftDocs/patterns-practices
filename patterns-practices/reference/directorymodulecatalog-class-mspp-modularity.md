---
TOCTitle: DirectoryModuleCatalog Class
Title: 'DirectoryModuleCatalog Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog'
ms:mtpsurl: 'directorymodulecatalog-class-mspp-modularity.md'
---

# DirectoryModuleCatalog Class

Represets a catalog created from a directory on disk.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
    public class DirectoryModuleCatalog : ModuleCatalog
```

```VB
'Declaration
Public Class DirectoryModuleCatalog
	Inherits ModuleCatalog
```

## Remarks

The directory catalog will scan the contents of a directory, locating classes that implement [IModule](/patterns-practices/reference/imodule-interface-mspp-modularity) and add them to the catalog based on contents in their associated [ModuleAttribute](/patterns-practices/reference/moduleattribute-class-mspp-modularity). Assemblies are loaded into a new application domain with ReflectionOnlyLoad. The application domain is destroyed once the assemblies have been discovered. The diretory catalog does not continue to monitor the directory after it has created the initialze catalog.

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
[Microsoft.Practices.Prism.Modularity.ModuleCatalog](/patterns-practices/reference/modulecatalog-class-mspp-modularity)  
Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog

## See Also

[DirectoryModuleCatalog Members](/patterns-practices/reference/directorymodulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  