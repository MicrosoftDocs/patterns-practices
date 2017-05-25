---
TOCTitle: 'AddModule Method (String, String, String, InitializationMode, String[])'
Title: 'ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleCatalog.AddModule(System.String,System.String,System.String,Microsoft.Practices.Prism.Modularity.InitializationMode,System.String[])'
ms:mtpsurl: 'addmodule-mthd-str-str-initializationmode-str.md'
---

Prism Class Library

# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String[])

Adds a groupless [ModuleInfo](moduleinfo-class-mspp-modularity.md) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

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
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](initializationmode-enumeration-mspp-modularity.md)

Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)[]

Collection of module names ([ModuleName](moduleinfo-modulename-property-mspp-modularity.md)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](modulecatalog-class-mspp-modularity.md)

The same [ModuleCatalog](modulecatalog-class-mspp-modularity.md) instance with the added module.

## See Also

[ModuleCatalog Class](modulecatalog-class-mspp-modularity.md)

[ModuleCatalog Members](modulecatalog-members-mspp-modularity.md)

[AddModule Overload](addmodule-mthd-str-str-initializationmode-str.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)

# ModuleCatalog.AddModule Method (String, String, String, InitializationMode, String())

Adds a groupless [ModuleInfo](moduleinfo-class-mspp-modularity.md) to the catalog.

**Namespace:** [Microsoft.Practices.Prism.Modularity](mspp-modularity-namespace.md)

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
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Name of the module to be added.

*moduleType*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

[Type](http://msdn.microsoft.com/en-us/library/42892f65) of the module to be added.

*refValue*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)

Reference to the location of the module to be added assembly.

*initializationMode*  
Type: [Microsoft.Practices.Prism.Modularity.InitializationMode](initializationmode-enumeration-mspp-modularity.md)

Stage on which the module to be added will be initialized.

*dependsOn*  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)()

Collection of module names ([ModuleName](moduleinfo-modulename-property-mspp-modularity.md)) of the modules on which the module to be added logically depends on.

### Return Value

Type: [ModuleCatalog](modulecatalog-class-mspp-modularity.md)

The same [ModuleCatalog](modulecatalog-class-mspp-modularity.md) instance with the added module.

## See Also

[ModuleCatalog Class](modulecatalog-class-mspp-modularity.md)

[ModuleCatalog Members](modulecatalog-members-mspp-modularity.md)

[AddModule Overload](addmodule-mthd-str-str-initializationmode-str.md)

[Microsoft.Practices.Prism.Modularity Namespace](mspp-modularity-namespace.md)
