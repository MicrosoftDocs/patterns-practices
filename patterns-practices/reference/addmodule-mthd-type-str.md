---
TOCTitle: 'AddModule Method (Type, String[])'
Title: 'ModuleCatalog.AddModule Method (Type, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.Type,System.String[])'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405869(v=PandP.50)'
---


# ModuleCatalog.AddModule Method (Type, array&lt;String&gt;)

Adds a groupless [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

public ModuleCatalog AddModule( Type moduleType, params string[] dependsOn )Public Function AddModule ( moduleType As Type, ParamArray dependsOn As String() ) As ModuleCatalog

### Parameters

moduleType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

dependsOn  
Type: array&lt;[System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)&gt;
Collection of module names ([ModuleName](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.modulename)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)
The same [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) instance with the added module.

## See Also

[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[AddModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.modulecatalog.addmodule)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
