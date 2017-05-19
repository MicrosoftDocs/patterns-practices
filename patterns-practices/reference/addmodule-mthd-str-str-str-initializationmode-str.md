---
TOCTitle: 'AddModule Method (String, String, String, InitializationMode, String[])'
Title: 'ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.String,System.String,System.String,Microsoft.Practices.Prism.Modularity.InitializationMode,System.String[])'
ms:mtpsurl: 'https://msdn.microsoft.com/en-us/library/Gg405873(v=PandP.50)'
---

Prism Class Library

# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[])

Adds a groupless [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50)) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
public ModuleCatalog AddModule(
	string moduleName,
	string moduleType,
	string refValue,
	InitializationMode initializationMode,
	params string[] dependsOn
)
```


### Parameters

*moduleName*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

[Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.initializationmode(v=pandp.50))

Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)[]

Collection of module names ([ModuleName](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo.modulename(v=pandp.50))) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50))

The same [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50)) instance with the added module.

## See Also

[ModuleCatalog Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50))

[ModuleCatalog Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog_members(v=pandp.50))

[AddModule Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String())

Adds a groupless [ModuleInfo](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo(v=pandp.50)) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))

**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```VB
'Declaration
Public Function AddModule ( 
	moduleName As String,
	moduleType As String,
	refValue As String,
	initializationMode As InitializationMode,
	ParamArray dependsOn As String()
) As ModuleCatalog
```


### Parameters

*moduleName*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

[Type](http://msdn2.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)

Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.initializationmode(v=pandp.50))

Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn2.microsoft.com/en-us/library/s1wwdcbf)()

Collection of module names ([ModuleName](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.moduleinfo.modulename(v=pandp.50))) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50))

The same [ModuleCatalog](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50)) instance with the added module.

## See Also

[ModuleCatalog Class](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog(v=pandp.50))

[ModuleCatalog Members](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog_members(v=pandp.50))

[AddModule Overload](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity.modulecatalog.addmodule(v=pandp.50))

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/en-us/library/microsoft.practices.prism.modularity(v=pandp.50))
