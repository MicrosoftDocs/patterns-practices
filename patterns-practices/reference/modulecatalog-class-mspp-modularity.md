---
TOCTitle: ModuleCatalog Class
Title: 'ModuleCatalog Class (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'T:Microsoft.Practices.Prism.Modularity.ModuleCatalog'
ms:mtpsurl: 'modulecatalog-class-mspp-modularity.md'
---


# ModuleCatalog Class

The ModuleCatalog holds information about the modules that can be used by the application. Each module is described in a [ModuleInfo](/patterns-practices/reference/moduleinfo-class-mspp-modularity) class, that records the name, type and location of the module. It also verifies that the ModuleCatalog is internally valid. That means that it does not have: Circular dependenciesMissing dependencies Invalid dependencies, such as a Module that's loaded at startup that depends on a module that might need to be retrieved. The ModuleCatalog also serves as a baseclass for more specialized Catalogs .

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
[ContentPropertyAttribute("Items")]
public class ModuleCatalog : IModuleCatalog
```

```VB
'Declaration
<ContentPropertyAttribute("Items")> 
Public Class ModuleCatalog
	Implements IModuleCatalog
```

## Inheritance Hierarchy

[System.Object](http://msdn.microsoft.com/en-us/library/e5kfa45b)  
&nbsp;&nbsp;Microsoft.Practices.Prism.Modularity.ModuleCatalog  
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.ConfigurationModuleCatalog](/patterns-practices/reference/configurationmodulecatalog-class-mspp-modularity)  
&nbsp;&nbsp;&nbsp;&nbsp;[Microsoft.Practices.Prism.Modularity.DirectoryModuleCatalog](/patterns-practices/reference/directorymodulecatalog-class-mspp-modularity)

## See Also

[ModuleCatalog Members](/patterns-practices/reference/modulecatalog-members-mspp-modularity)  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)