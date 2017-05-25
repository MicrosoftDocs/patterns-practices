---
TOCTitle: 'AddModule Method (String, String, String[])'
Title: 'ModuleCatalog.AddModule Method (String, String, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.String,System.String,System.String[])'
ms:mtpsurl: 'addmodule-mthd-str-str-initializationmode-str.md'
---

Prism Class Library

ModuleCatalog.AddModule Method (String, String, array&lt;String&gt;)
==================================================================================

Adds a groupless [ModuleInfo](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


public ModuleCatalog AddModule( string moduleName, string moduleType, params string[] dependsOn )Public Function AddModule ( moduleName As String, moduleType As String, ParamArray dependsOn As String() ) As ModuleCatalog

### Parameters

moduleName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
Name of the module to be added.

moduleType  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

dependsOn  
Type: array&lt;[System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)&gt;
Collection of module names ([ModuleName](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfo.modulename)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)
The same [ModuleCatalog](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog) instance with the added module.

See Also
--------


[ModuleCatalog Class](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.modulecatalog)

[ModuleCatalog Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.modulecatalog)

[AddModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.modulecatalog.addmodule)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
